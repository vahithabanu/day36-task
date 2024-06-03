## Output Screenshots:

## Query

### db.codekata.find()

![output screenshot](./image/codekata-1.png)

![output screenshot](./image/codekata-2.png)

### db.companydrives.find()

![output screenshot](./image/company-1.png)

![output screenshot](./image/company-2.png)

### db.mentors.find()

![output screenshot](./image/mentor-1.png)

### db.topics.find()

![output screenshot](./image/topics-1.png)


![output screenshot](./image/topics-2.png)

### db.usertask.find()

![output screenshot](./image/usertask-1.png)

![output screenshot](./image/usertask-2.png)

### Question 1 -output:

### Query: db.topics.find({month:"october"})


![output screenshot](./image/ques1-1.png)

### Question 2 -output:

### Query: db.companydrives.find({date:{$gt:"2020-10-15",$lt:"2020-10-31"}})



![output screenshot](./image/ques2.png)

### Question 3 -output:

### Query: 
      db.company_drives.find().forEach(function(value){
    print("Company Name : "+value.company_name);
    print("Students Appeared : "+value.students_appeared);
       })


![output screenshot](./image/ques3-1.png)

### Question 4 -output:

### Query: 
    db.codekata.find().forEach(function(value){
      
    print("Name : "+value.user_name);
    print("Problems Solved : "+value.problems_solved)
    })

![output screenshot](./image/ques%204.png)

### Question 5 -output:

### Query: db.mentors.find({mentees_count:{$gt:15}})

![output screenshot](./image/ques%205.png)

### Question 6 -output:

### Query: 
      db.usertask.find({date:{$gt:"2020-10-15",$lt:"2020-10-31"}}).forEach(function(value){
    print("Name : "+value.user_name);
    print("Attendance :"+value.attendance);
    print("Task : "+value.task_submission)
     })

![output screenshot](./image/ques%206.png)