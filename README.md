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

<h1>Partie 1</h1>

<img width="1000" height="500" alt="Capture1" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/efe5f95d-607d-4248-9046-5a413cab0896">
<img width="1000" height="500" alt="Capture2" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/a57c7923-fb85-47f4-a708-dc5a73b40bf7">
<img  width="1000" height="500" alt="Capture3" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/08394fc4-ddb0-4a67-921b-4da037efb334">
<img  width="1000" height="500" alt="Capture4" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/4027c680-8d98-41f0-9bf6-00f946059163">
<img  width="1000" height="500" alt="Capture5" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/c434ac6b-6a17-4a64-88e5-9873a03ac3cd">
<img  width="1000" height="500" alt="Capture6-par mp" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/55522ad8-544e-4e92-bf04-b350a57f1d71">
<img  width="1000" height="500" alt="Capture7-par refresh token" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/830c76d4-0d53-494a-bcb5-33efb98b0c53">
<img  width="1000" height="500" alt="Capture8-par client secret" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/06b6ccc0-d8dd-489a-8761-33fce7a14c6a">
<img  width="1000" height="500" alt="Capture9" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/2c927ee9-37b2-4861-9b3b-819a13b60066">
<img  width="1000" height="500" alt="Capture10" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/4729374e-302b-4d8a-955d-6da591c41575">
<img width="1000" height="500" alt="Capture11" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/bf4586e5-e072-47d6-9c76-2cf98be12366">
<img  width="1000" height="500" alt="Capture12" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/3f6a7f53-13df-4470-84d4-229f75835d39">
<img  width="1000" height="500" alt="Capture13-graphQl" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/366b19c6-9424-42b9-a523-fd29bf6d09f2">
<img  width="1000" height="500" alt="Capture14" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/860a9e71-54ba-481f-b755-afd0e48d10d3">
<img  width="1000" height="500" alt="Capture15" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/eca72287-c70a-4553-8881-adff1796a8ee">
<img  width="1000" height="500" alt="Capture16" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/4c80c37f-bad9-4373-adc8-23f8acc463d5">
<img  width="1000" height="500" alt="Capture17-ConfigKC" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/141b805f-5fdb-4d17-bdd0-114dd8ad9943">
<img  width="1000" height="500" alt="Capture18" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/0956c761-05e4-4464-8f13-30cf94ceca26">
<img width="1000" height="500" alt="Capture19" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/cba17448-699c-40cd-ab19-2c8bf9bce7dc">
<img  width="1000" height="500" alt="Capture20" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/b979b096-aa9d-4bc1-8849-ecfb2f661b00">

<h1>Partie 2</h1>
<img  width="1000" height="500" alt="Capture1" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/6aa7f453-538e-4fde-b085-2fd3f64367de">
<img  width="1000" height="500" alt="Capture2" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/8d6e8a44-8e89-4e6c-937e-01d4566046b2">
<img  width="1000" height="500" alt="Capture3" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/66fc0343-1aec-4246-8b5f-a119d6c594dc">
<img  width="1000" height="500" alt="Capture4" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/75b62342-89f8-4b1f-9d2d-6cac9fef7ce9">
<img  width="1000" height="500" alt="Capture5" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/68b4145a-a4e2-4fb8-8b8b-e06d638184fb">
<img  width="1000" height="500" alt="Capture6" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/323b7573-d213-42d5-83b4-d6c7ec4a8846">
<img  width="1000" height="500" alt="Capture7" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/b430f979-acbe-456b-a5ab-0e70cbea4e28">
<img  width="1000" height="500" alt="Capture8" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/a000d84b-daf0-42e1-b812-efacad2671f9">
<img width="1000" height="500" alt="Capture9" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/e63075d5-b081-4800-8f2f-f91fbe44ae27">
<img  width="1000" height="500" alt="Capture10" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/0343e708-505f-4f3e-8a8b-0f53f6df27c3">
<img  width="1000" height="500" alt="Capture11" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/3ce70809-ed2f-43f0-aff1-033ab4ec0f49">
<img width="1000" height="500" alt="Capture12" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/1699adfc-93e7-47e6-9ea1-ff26ab947bf8">
<img width="1000" height="500" alt="Capture13" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/e9ae894c-c999-4110-9287-9f29b753096a">
<img  width="1000" height="500" alt="Capture14" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/bdda03bf-b98d-4612-9b90-fa7ad18547ff">
<img  width="1000" height="500" alt="Capture15" src="https://github.com/hajarmanyani/activite7_keycloak_oauth2_authentication/assets/93662714/c006e8e8-fd4e-4a35-9571-86c71e0a0477">








