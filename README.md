# imgur-clone
A web application that works similarly to Imgur. It allows users to create an account/login with password hashing implemented. Users can view images, comment on albums, create albums, upload images and, like/favorites albums.

## Technologies
• Java 1.8

• Spring Framework 4.3.27

    - Spring ORM    
    - Spring MVC
    
• Hibernate 4.3.11

• Postgres 42.2.18

• JUnit 4.12

• Amazon AWS S3 SDK

• Apache Tomcat


## Getting Started

### Pre-requisites
Please ensure you have the following installed prior to cloneing this repository:
- Java 1.8 SDK
- Maven


### Required Files
• AwsCrendtials.properties

        AWSAccessKeyId=YOUR_AWS_ACCESS_KEY
        AWSSecretKey=YOUR_AWS_SECRET_KEY
        region=us-east-1

• datasource.properties

      datasource.url=your_rds_instance
      datasource.username=your_database_username
      datasource.password=your_database_password


## Running the Application

- maven package the spring application to a war
- deploy the war file to a tomcat server and run the server


Start the angular project with 
`ng serve -o`


