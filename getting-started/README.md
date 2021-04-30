# Getting Started

### Create Project

- Install last version Node.js
- Install ``npm install @angular/cli``
- Create ``ng new [your-app-name]``

### Install/Config Ionic

- Install ``npm install @ionic/angular``
- Config ``ng add @ionic/angular``
- Init multi-app ``ionic init --multi-app --type=angular --project-id=getting-started --default``
- Init project ``ionic init "Draft Fingerprint" --type=angular --force``

### Install/Config Capacitor

- Install ``npm install @capacitor/core @capacitor/cli``
- Config ``npx cap init --web-dir dist/getting-started "Draft Fingerprint" com.angular.ionic.draft.fingerprint``

### Native Android Project

- Build ``ionic build``
- Add Android ``ionic cap add android``
- Open native ``ionic cap open android``

### Live Reload

- Run ``ionic cap run android -l --external``

### Build and Sync

- Run ``ionic cap build android``