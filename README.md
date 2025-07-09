# Projet-PainLessMesh
Projet de BTS utilisant une communication en PainLessMesh pour créer un réseau mailler avec des ESP32
/***********************************************

PROGRAMME "LEDUSBToPainLess2"

Assure une communication entre plusieurs ESP32, 

IMPORTANT
Avant de lancé le programme verifier si les ESP32 ont bien les même parametres dans
#define MESH_PREFIX "MonMesh"
#define MESH_PASSWORD "password123"
#define MESH_PORT 5555

Pour communiquer il faut ouvrir un terminal serie relié a un ESP32 en USB pour pouvoir envoyer des messages
