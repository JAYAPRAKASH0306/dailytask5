# dailytask5
for a given json iterate over all loops (for,for in,for of,for each)
for in method
const personaldetails = {
  "name": "Jayaprakash",
  "age": 23,
  "address": {
    "street": "123 Main Street",
    "city": "coimbatore ",
    "state": "Tamilnadu"
  }
};

for (const key in personaldetails) {
  console.log(key,personaldetails[key]) ;

}
for of method
const personaldetails = {
  "name": "Jayaprakash",
  "age": 23,
  "address": {
    "street": "123 Main Street",
    "city": "coimbatore ",
    "state": "Tamilnadu"
  }
};

for (const key of Object.keys( personaldetails)) {
  console.log(key,personaldetails[key]) ;

}
for each
const personaldetails = {
  "name": "Jayaprakash",
  "age": 23,
  "address": {
    "street": "123 Main Street",
    "city": "coimbatore",
    "state": "Tamilnadu"
  }
};

personaldetails.forEach((keys,value) => {
  console.log(keys, value);
});

2.created resume using JSON

let resume={
  "name": "jayaprakash",
  "email": "jayaprakashk0306@gmail.com",
  "phone": "6379143960",
  "education": [
    {
      "college": "bharathiyar  University",
      "degree": "Master of business administration",
      "year": 2023
    }
  ],
  "work experience": [
    {
      "company": "sitics logistics solution",
      "position": "SAP executive ",
      "start_date": "sep 2021",
      "end_date": "Present"
    }
  ],
  "skills": [
    "sap",
    "Ms office ",
    "Coding"   
  ]}
  console.log(resume);


