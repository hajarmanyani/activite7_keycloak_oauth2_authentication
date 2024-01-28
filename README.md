# Spring project with angular and thymeleaf activity 7.
---------------------------------------
### Before you start
+ Download Keycloak
+ Download and extract keycloak.zip from the Keycloak website.
+ After extracting this file, you should have a directory that is named keycloak.
+ On Windows, run: bin\kc.bat start-dev
## Create an admin user
+ Keycloak has no default admin user. You need to create an admin user before you can start Keycloak.
+ Open http://localhost:8080/.
+ Fill in the form with your preferred username and password.
## Log in to the Admin Console
+ Go to the Keycloak Admin Console.
+ Log in with the username and password you created earlier.

# Démonstration Keycloak
<h2>1. Télécharger Keycloak 23</h2>
<h2>2. Démarrer Keycloak</h2>
<h2>3. Créer un compte Admin</h2>
<h2>4. Créer une Realm</h2>
<h2>5. Créer un client à sécuriser</h2>
<h2>6. Créer des utilisateurs</h2>
<h2>7. Créer des rôles</h2>
<h2>8. Affecter les rôles aux utilisateurs</h2>
<h2>9. Avec PostMan :</h2>
    <h3>- Tester l'authentification avec le mot de passe</h3>
    <h3>- Analyser les contenus des deux JWT Access Token et Refresh Token</h3>
    <h3>- Tester l'authentification avec le Refresh Token</h3>
    <h3>- Tester l'authentification avec Client ID et Client Secret</h3>
    <h3>- Changer les paramètres des Tokens Access Token et Refresh Token</p></h3>


<img width="900" height="450" alt="Capture1" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/587d5f47-ffd3-4dea-ba61-c9ce361c1230">
<img width="900" height="450"  alt="Capture2" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/857ef529-3fce-4043-a116-0053d146068e">
<img width="900" height="450"  alt="Capture3" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/c521123b-9a06-41c2-beb2-1b8d0977dda3">
<img width="900" height="450"  alt="Capture4" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/97910b05-a8a5-46f6-b1f6-9dfd1d1f9b2c">
<img width="900" height="450"  alt="Capture5" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/5cdafd01-e062-454a-a638-1ed3f261e104">
<img width="900" height="450"  alt="Capture6-par mp" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/67cefc5c-3f55-439a-92d0-5320bc303079">
<img width="900" height="450"  alt="Capture7-par refresh token" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/57e38b35-6089-426b-94eb-650e40fb8737">
<img width="900" height="450"  alt="Capture8-par client secret" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/4b3cd2c5-b05c-4705-be80-e9316983bc43">
<imgwidth="900" height="450"  alt="Capture9" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/3b35cb23-7e32-48ee-8f0d-e98739410764">
<img width="900" height="450"  alt="Capture10" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/87bf9a8f-420f-4298-84f1-7091d60089e3">
<img width="900" height="450"  alt="Capture11" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/630f4bc1-2d7d-4a1e-a915-f4a3021c4849">
<img width="900" height="450"  alt="Capture12" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/d80639da-40d8-4936-b63d-e17a1c14609d">
<img width="900" height="450"  alt="Capture13-graphQl" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/764f77ad-98b6-46ad-a9ba-e542df81a38e">
<img width="900" height="450"  alt="Capture14" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/64d22218-b03d-4974-8e24-626d51d7a3b6">
<img width="900" height="450"  alt="Capture15" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/33ca3fc3-08f5-4199-a2e1-9191c7b5e78c">
<img width="900" height="450"  alt="Capture16" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/355a22af-f896-4a4d-bf6d-067f7e68181e">
<img width="900" height="450"  alt="Capture17-ConfigKC" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/5cdfdf55-49db-45b1-b679-e38f98a42f9b">
<img width="900" height="450"  alt="Capture18" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/b419b3d3-a3cb-4aa0-aace-d57b2e215077">
<img width="900" height="450"  alt="Capture19" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/079e2adc-2c47-4a3f-9614-b3a325de7260">
<img width="900" height="450"  alt="Capture20" src="https://github.com/hajarmanyani/Keycloak_microservices_Rest_GraphQl/assets/93662714/56473f7d-c59d-4008-bf54-787c121871a6">
