<h1 align="center">
  Control the expenses
</h1>

<p align="center">
  This system is used to control the expenses. You can register employee, places that you worked/working to manage your expenses.  
</p>


</br>
  
<p align="center">
  <a href="#globe_with_meridians-Technologies-and-Concepts-Implemented">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
   <a href="#gear-Architecture">Architecture</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
   <a href="#round_pushpin-demo">Demo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#wrench-How-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-Licence">Licence</a>
</p>

## :globe_with_meridians: Technologies and Concepts Implemented

This project was developed using:

- ASP NET Core 3.1
- Dapper 2.0.123
- SQL Server
- AutoMapper 11.0.1
- HTML and CSS
- Bootstrap
- jQuery

Concepts/Techniques used in:
- Data Transfer Object [DTO]
- Repository Pattern
- Dependency Injection

## :gear: Architecture

```🌐
src
├── 📂 0- Portal
|   ├── 📂 Controllers
|   ├── 📂 Utils
|   ├── 📂 Views
├── 📂 1- Domain
|   ├── 📂 Business
|   ├── 📂 IBusiness
|   ├── 📂 IRepository
|   ├── 📂 Models
├── 📂 2- Data
|   ├── 📂 EntityData
|   ├── 📂 Repository
├── 📂 3- Utils
|   ├── 📂 Commom
|   ├── 📂 CrossCutting
├── 📂 4- Migration
|   ├── 📂 Scripts
├── 📂 5- Outros
|   ├── 📂 dlls

```

## :round_pushpin: Demo
![image](https://github.com/heberGustavo/administrativo-imperial/assets/44476616/ec5c2fa3-e828-4ba9-9d9c-5fe0e3f09d73)



## :wrench: How to use

Clone that application using [Git](https://git-scm.com) and follow the next steps:

```bash
# 1. Clone this repository
$ git clone https://github.com/heberGustavo/administrativo-imperial.git

# 2. Open the project in Visual Studio

# 3. Execute the build

# 4. Change the Connection String. To modify follow this path:
  4.1 - Portal > AdministrativoImperial.Portal > appsettings.json
  4.2 - Modify the value to "CONNECTION_STRING" and "CONNECTION_STRING_DEBUG"

# 5. Run the application

```


## :memo: Licence 
This project is under the MIT license. See the [LICENSE](https://github.com/heberGustavo/administrativo-imperial/blob/main/LICENSE) for more information.


## Autor

| [<img src="https://avatars.githubusercontent.com/u/44476616?v=4" style="max-width: 100%;width: 90px;"><br><sub>Heber Gustavo</sub>](https://github.com/heberGustavo) |
| :---: |
|[Linkedin](https://www.linkedin.com/in/heber-gustavo/)|

