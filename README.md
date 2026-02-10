# CST8915 Lab 2 - CST8915 Full-stack Cloud-native Development

**Student Name**: [Corey Mark-Stewart]
**Student ID**: [040770982]
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Winter 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/BoOzbOm6SSU)

---

## Reflection Questions

1. What changes did you make to the order-service and product-service to comply with the Configurations and Backing Services factors of the 12-Factor App methodology?
  in order seriver and product service, I had to load from a .env file and change the port on both to 3000 and 3030 for order had to provide the rabbitmq service url with the username and password. As for product only the port was add to the .env 
  
2 Why is it important to use environment variables instead of hard-coding configurations in your application?
  hard coded varible remain seen in the github commit history. providing it through the enviroment variable through the .env file so it's hidden from the public.
 
3. Why is it important to have separate repositories for each microservice? How does this help maintain independence and scalability of each service?
  as part of the 12 factor app. Dependancies are important to be issolated in each mircroservice, so that we don't get a "but it works on my machine". thus making it more scalable, there's no unknow dependancy that will crash the service.

Also when making the product service, it has not be created in the same resouce group.

---

store-front: https://github.com/CoreyCauterize/store-front
order-service: https://github.com/CoreyCauterize/order-service
product-service: https://github.com/CoreyCauterize/product-service

