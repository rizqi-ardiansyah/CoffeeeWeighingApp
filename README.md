# Smart Coffee Weighing

A coffee weighing system equipped with an Internet of Things (IoT) device is an innovation that aims to improve efficiency and accuracy in the process of weighing coffee beans. The background to creating this system is based on the need for the coffee industry to better control and monitor the quantity and quality of coffee beans used in the production process

 ![image](https://github.com/rizqi-ardiansyah/CoffeeeWeighingApp/assets/86498942/5d0e46e8-3165-4ae1-b9f8-6de2162286fe)

# Feature

### 1. Login

- Login can be done by the admin or the employee. Admins can access all features, while employees only have a few features
  
  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/d7e3e0a7-2663-4f9f-9d11-fb548963a4be" width="800" />

  *Seeder the fake account first so you can get a random account to log into the system*
 
### 2. Dashboard

- The dashboard displays information on the number of workers, the amount of coffee data, and the total weight of coffee

  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/df4b8d6d-ce5b-40d2-8094-7fd7fe73462d" width="800" />

### 3. Manage Workers

- Worker management is used to manage worker data in which there are features to add data, edit and delete data

  *Employee data display*

  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/6d9d0d63-42dd-4022-844a-f1e26b3d7237" width="800" />

  *Display adds employee data*
  
  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/334e89ae-4b5f-40a0-811f-63d793bc1873" width="800" />

  *Display updates employee data*
  
  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/6fef8739-2f9f-4c83-bc98-c879c848ecf9" width="800" />

  *Display deletes employee data*

  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/04f1ada6-b9ef-4d46-aace-f1420341afa3" width="800" />

### 4. Manage Coffee

- Coffee management is used to manage the weighing process of coffee that is weighed using IOT. The weight of this copy will be sent automatically from the item detection sensor

  *Coffee data display*
  
  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/30a44f05-87ba-4256-8a3c-99b3c61ab676" width="800" />
  
  *Display adds coffee data manually*
  
  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/e242f35e-5d6a-4b89-a306-b5383bf18c37" width="800" />
  
  *Display deletes coffee data*
  
  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/3b4c3a23-dbc0-4572-b749-66ee55562aee" width="800" />

### 5. Report

- The report feature will assist employees in accumulating the data that has been obtained and can be printed in excel and pdf format

  <img src="https://github.com/rizqi-ardiansyah/simoyam/assets/86498942/7d9c2d32-c675-4be9-a33d-eb6473e6859f" width="800" />

# Installation

1. Clone the repository
   
2. Install composer
    ```bash
    composer install
    ```
    
3. Copy file .env.example
     ```bash
    cp .env.example .env
    ```
     
5. Generate the key
    ```bash
    php artisan key:generate
    ```

8. Do the migrations first
    ```sh
    php artisan:migrate
    ```

9. Do the seeder first
    ```sh
    php artisan db:seed
    ```
    
10. Run projects
    ```sh
    php artisan serve
    ```
    
# License

The MIT License (MIT) 2023 - [Rizqi Ardiansyah](https://github.com/rizqi-ardian/). Please have a look at the [LICENSE.md](LICENSE.md) for more details.
