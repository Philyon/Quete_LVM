# Solution de la quête LVM

Sommaire :
1. L'ajout d'un PV à debian-vg et au moins le doublement des Total PE
2. La création d'un snapshot du LV home
3. Il y a bien création d'un dossier home-snap et montage du snapshot dans ce dossier
4. L'affichage du contenu de home-snap affiche un contenu identique à /home
5. L'affichage des systèmes de fichiers actuellement montés n'affiche plus /home-snap
6. L'affichage des LV n'affiche plus le snapshot et le LV home n'est plus la source d'aucun snapshot

## 1. L'ajout d'un PV à debian-vg et au moins le doublement des Total PE
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/52b912c8-64b7-4e93-946e-f80cbc1ca0e4" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/4dbdc129-7e01-4ee3-ac18-a40ccfa85304" alt=""></p>
<br><p align="center"><img width="40%" src="https://github.com/user-attachments/assets/ca5a4aa4-caa9-47f5-839a-b22fd1188c88" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/81ada624-b3df-4565-97c1-70e00a6beba0" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/6c638bdb-a0ee-454b-8edd-8a951b0974a3" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/5e8efc1c-4482-4fbf-b3bc-0ff4d0e99142" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/3dd4c2d3-35ec-4586-96c3-d2fe43bb2883" alt=""></p>
## 2. La création d'un snapshot du LV home
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/a42f2ac3-2fe8-4660-ab50-17aa2b2d562d" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/1d68d7f9-d149-4483-916a-52b8f7240751" alt=""></p>
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/cfbd2d30-ebd8-4339-82ff-733f51986a07" alt=""></p>
## 3. Il y a bien création d'un dossier home-snap et montage du snapshot dans ce dossier
## 4. L'affichage du contenu de home-snap affiche un contenu identique à /home
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/9598fb7b-9f72-49d2-afd2-3c9612dee25e" alt=""></p>
## 5. L'affichage des systèmes de fichiers actuellement montés n'affiche plus /home-snap
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/eb91fb4d-39a3-4890-9f96-432ee974afd9" alt=""></p>
## 6. L'affichage des LV n'affiche plus le snapshot et le LV home n'est plus la source d'aucun snapshot
<br><p align="center"><img width="70%" src="https://github.com/user-attachments/assets/8069f6a9-df3a-48cf-9fb2-d56c4246d7ab" alt=""></p>
## Quête terminée :tada: :tada: :tada:
