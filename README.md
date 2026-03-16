# The 12 Golden Sentences (English)


### 1️⃣ Present – State
**The apple is red.**  
*La manzana es roja.*

---

### 2️⃣ Possession
**This is John’s apple.**  
*Esta es la manzana de John.*

---

### 3️⃣ Present – Action
**I give the apple to John.**  
*Le doy la manzana a John.*

---

### 4️⃣ Pronouns
**We give the apple to him.**  
*Le damos la manzana a él.*

---

### 5️⃣ Third Person
**He gives it to John.**  
*Él se la da a John.*

---

### 6️⃣ Pronouns (She)
**She gives it to him.**  
*Ella se la da a él.*

---

### 7️⃣ Question
**Is the apple red?**  
*¿La manzana es roja?*

---

### 8️⃣ Plural
**The apples are red.**  
*Las manzanas son rojas.*

---

### 9️⃣ Modal Verb (Must)
**I must give it to him.**  
*Debo dársela a él.*

---

### 🔟 Intention
**I want to give it to her.**  
*Quiero dársela a ella.*

---

### 1️⃣1️⃣ Future
**I will know tomorrow.**  
*Sabré mañana.*

---

### 1️⃣2️⃣ Past
**I ate the apple.**  
*Comí la manzana.*








# GIT

### subir readme
git init                                                  

git add .                                                

git commit -m "Initial commit"                          

git branch -M main                                

git remote add origin https://                    

git push -u origin main                     



### subir archivos creados desde tu pc
```bash
pwd                                     # muestra la ruta completa de la carpeta en la que estás parado ahora mismo.
ls                                      # lista los archivos y carpetas que hay en la carpeta actual.

git pull                                # actualizar tu carpeta del proyecto si se hizo cambios desde git hub

///trabajas (creas/edita archivos)

git status                              # Te dice: “¿Qué cambió?”, Qué archivos están nuevos, cuáles editaste, cuáles ya están listos para commit

git add .                               # Te dice: “Estos archivos sí van al próximo guardado (commit)”.
                                                   # *git add clase1/* = agrega esa carpeta y lo que tenga.
                                                   # *git add* . = agrega todo lo que cambió.

git commit -m "..."                     # Hace el “guardado oficial” en tu PC (historial de Git).
git push                                # Si tu rama ya está vinculada al remoto, *git push* basta.
                                        # Si no está vinculada, usarías: *git push -u origin main*
```
### crear carpetas y archivos desde git bash

```bash
cd /c/ruta/a/tu/repo                           # Entrar a la carpeta de tu repositorio

mkdir pronunciation                            # Crear una carpeta llamada pronunciation
touch pronunciation/PRONUNCIATION_HACKS.md     # Crear un archivo Markdown dentro de esa carpeta

git status                                     # Ver el estado del repositorio  
git add pronunciation/                         # Le dices a Git: “incluye todo lo que está dentro de pronunciation/ en el próximo commit”.
git commit -m "Add pronunciation folder"       # Guarda oficialmente esos cambios en el historial del repo (local).
git push origin main                           # Envía tus commits a tu repositorio remoto (GitHub), al remoto llamado origin, rama main.
```
### Extras
```bash
agregar  ---> git add archivo
eliminar ---> git rm archivo

editor de texto de Git (Vim) --->     ESC
                                     :wq
                                      ENTER

subir imagen ---> ![Tiempos verbales](../../assets/tiemposVerbales.png)


clonar repositorio y haci editarlo ----> git clone https://github.com/Marco404-Dev/Sistemas-Operativos.git

comprobar si estas dentro del repositorio ---> ubicate primero la carpeta del github y coloca -->  git remote -v
```














