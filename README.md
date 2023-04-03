Micro Personnel is a human resources management system that separates the front and back ends, and the project is developed with SpringBoot+Vue.

Demonstration address:

Project address: [https://github.com/lenve/vhr](https://github.com/lenve/vhr)

##tips

Since the entire project has many functions and is relatively complicated, it is developed in multiple phases. At present, the first phase of the authority management module has been developed, and other modules are still under development. Considering that the authority management module is relatively independent and does not conflict with the functions of other modules, and the authority management after the separation of front and back ends is a pain point for many small partners, so this project is open sourced in advance for small partners to study. **But friends, please note that only the authority management module has been completed, so you cannot see all the functions in this project, except the authority management related modules. There are two main modules related to authority management, namely [System Management -> Basic Information Settings -> Authority Group] to manage the relationship between roles and resources, and [System Management -> Operator Management] to manage the relationship between users and roles. **

## technology stack

### Backend technology stack

1. Spring Boot
2. Spring Security
3. MyBatis
4. MySQL

### Front-end technology stack

1. Vue
2. Element UI
3. axios
   4.vue-router

There are other trivial technologies that are not listed one by one.

## Quick deployment

1. Clone the project to the local `git@github.com:lenve/vhr.git`

## Documentation

The document is a detailed record of some problems encountered in the project development process, mainly to help those who have no foundation to quickly understand the project.

1. [Privilege database design] (https://github.com/lenve/vhr/wiki/1.%E6%9D%83%E9%99%90%E6%95%B0%E6%8D%AE%E5 %BA%93%E8%AE%BE%E8%AE%A1) 2.[Server environment construction](https://github.com/lenve/vhr/wiki/2.%E6%9C%8D%E5%8A%A1%E7%AB%AF%E7%8E%AF% E5%A2%83%E6%90%AD%E5%BB%BA)
2. [Dynamic processing of the relationship between roles and resources] (https://github.com/lenve/vhr/wiki/3.%E5%8A%A8%E6%80%81%E5%A4%84%E7%90 %86%E8%A7%92%E8%89%B2%E5%92%8C%E8%B5%84%E6%BA%90%E7%9A%84%E5%85%B3%E7%B3%BB )
3. [Password encryption and salting](https://github.com/lenve/vhr/wiki/4.%E5%AF%86%E7%A0%81%E5%8A%A0%E5%AF%86 %E5%B9%B6%E5%8A%A0%E7%9B%90)
4. [Unified processing of server-side exceptions] (https://github.com/lenve/vhr/wiki/5.%E6%9C%8D%E5%8A%A1%E7%AB%AF%E5%BC% 82%E5%B8%B8%E7%9A%84%E7%BB%9F%E4%B8%80%E5%A4%84%E7%90%86)
5. [Axios request encapsulation, unified handling of request exceptions](https://github.com/lenve/vhr/wiki/6.axios%E8%AF%B7%E6%B1%82%E5%B0%81%E8 %A3%85,%E8%AF%B7%E6%B1%82%E5%BC%82%E5%B8%B8%E7%BB%9F%E4%B8%80%E5%A4%84%E7% 90%86)
6. [Hang the request method to Vue](https://github.com/lenve/vhr/wiki/7.%E5%B0%86%E8%AF%B7%E6%B1%82%E6%96 %B9%E6%B3%95%E6%8C%82%E5%88%B0Vue%E4%B8%8A) 8.[Save login status](https://github.com/lenve/vhr/wiki/8.%E7%99%BB%E5%BD%95%E7%8A%B6%E6%80%81% E7%9A%84%E4%BF%9D%E5%AD%98) 9.[Dynamically load components after successful login](https://github.com/lenve/vhr/wiki/9.%E7%99%BB%E5%BD%95%E6%88%90%E5%8A% 9F%E5%90%8E%E5%8A%A8%E6%80%81%E5%8A%A0%E8%BD%BD%E7%BB%84%E4%BB%B6)
7. [Role resource relationship management] (https://github.com/lenve/vhr/wiki/10.%E8%A7%92%E8%89%B2%E8%B5%84%E6%BA%90% E5%85%B3%E7%B3%BB%E7%AE%A1%E7%90%86) 11.[User role relationship management](https://github.com/lenve/vhr/wiki/11.%E7%94%A8%E6%88%B7%E8%A7%92%E8%89%B2% E5%85%B3%E7%B3%BB%E7%AE%A1%E7%90%86)
