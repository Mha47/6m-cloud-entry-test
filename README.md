# Cloud Infrastructure Engineering - (6 Months) Entry Assessment

## Objective

This assessment aims to test your resourcefulness, the ability to understand IT concepts, and produce a viable answer to the problems listed.

---
## Submission

- Create an account in github.com
- Fork this repository to your account
- Use the online editor to edit this file (README.MD)
- Save your changes
- Submit the URL of this repository 
- Ensure your URL is publicly accessible

---
## Expected Audience

- Individuals with an IT background to diversify/expand their skills and/or intending to switch to a software developer role.
    - Those with IT or Engineering degree/diploma, or
    - Those with IT or Engineering experience professionally
- Individuals with systems and infrastructure administration background.
- Individuals who have attended basic infrastructure or cloud courses.

---

## Problems

Please attempt the solve the problems described:

**Question 1 - IP Address**

What is the Bash command to discover the IP Address of `www.skillsunion.com`?

```sh
# dig
```

---

**Question 2 - Copy a Directory**

What is the command to copy a directory from `~/my_project` to `/etc/projects`?

```sh
# cp -r ~/my_project /etc/projects 
```
---

**Question 3 - Shell Scripting**

Implement a bash script that does the follow:
1. Convert a string "one,two,three" into an array delimited by comma (,).
1. Loop through the array and print each element.

```sh
# 
numbers="one,two,three"

IFS="," read -r -a numbers_array <<< "${numbers}"
for number in "${numbers_array[@]}"; do
echo "number: ${number}"
done
```

---

**Question 4 - System Architecture Diagram**

Use [draw.io](draw.io) to draw a system architecture diagram as described below:

- A load balancer to manage request between 4 application servers.
- The load balancer is connected to the internet gateway.
- All application servers are connected to a cluster of database.
- The cluster of database contains an instance for reading and another instance for writing.
- The database must not be connected to the internet gateway.

Share the link to your image of diagram.

https://drive.google.com/file/d/15XGEd2bHatZcPS-Oj04mBZc4TYO6Octl/view?usp=sharing

---

**Question 5 - System Error Management**

Alan has deployed his web application to Amazon Web Service. Unfortunately, the web application encountered errors as complained by the customers (public users). Whenever there is a complaint, Alan would take a long time to trace the issue and get back to the customers. 

*Q5A: Which of the following described the scenario given?*

A - The principle of security is not applied.

B - The principle of observability is not applied.

C - The principle of availability is not applied.

D - The principle of performance is not applied.

*Q5B: What do you suggest could be done to improve the situation?*

```
B - The Principle of observability is not applied
There is a need to diversify monitoring metrics to include new metrics such as logs, alerts, traces and multiple infrastructural components. With the insights gathered, Alan would be able to address known issues and help customers faster. 

What do you expect to gain? I hope to gain the knowledge and skills required to launch a successful and meaningful career in the field of cloud engineering. Hopefully specializing in Dev/ops.  

What are your career goals 12 months after grad? I intend to complete the relevant cloud certifications and improve my knowledge and employability in this field. 

How you determine SCTP will achieve your goals? From what i have read, this SCTP course will provide hands on training and the relevant skills required for the cloud engineer role making it easier for me to get a foothold in the industry. 

What are your past/current skills that will help you succeed after grad? I am no stranger to constantly gaining new knowledge and upskilling myself having successfully completed my part time bachelor's degree. I am resourceful and will do my best to clear any doubts i have. I understand the importance of having a good network and intend to network with as many veterans in the field as i can. 

What obstacles? I foresee the learning curve to be very steep as i do not come from an IT engineering background but i believe i will be able to overcome this challenge by consulting with mentors to clear my doubts and constantly reading up and keeping up to date with recent trends.

```

---

END
