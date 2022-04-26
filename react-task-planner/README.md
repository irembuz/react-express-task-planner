# React Task Planner Projesi

Kullanıcının yapacağı taskları günlük, haftalık ve aylık olarak planlayabildiği bir görev yöneticisi projesidir.

Projede günlük, haftalık ve aylık tasklarımızı görebildiğimiz; Day, Week ve Month sayfalarına yönlenebildiğimiz bir SideBar bulunmaktadır.

Header kısmında Today butonu, ayları değiştirebileceğimiz ikonlar ve yeni task ekleyebileceğimiz Add Task butonu bulunmaktadır.

Today butonuna tıkladığımızda bizi bugünün tarihine götürmektedir.

Add Task butonuna tıkladığımızda pop-up ekranı çıkmaktadır.

Add Task butonuna tıklayarak ya da Month veya Week sayfalarından istediğimiz bir gün seçerek tasklarımızı ekleyebiliriz.

Eklediğimiz taskların üstüne tıkladığımızda çıkan pop-up ekranından taskımızı silebilir veya düzenleyebiliriz.

## Projede Kullandığım Teknolojiler

- React
- Context API
- TypeScript
- CSS3 (Tailwind CSS)
- HTML5
- Dayjs

## Projenin Eksikleri

Header componentinde bulunan ikonlar sayesinde ayları değiştirebiliyoruz. Bu ikonları Day ve Week sayfalarına da ekleyerek gün ve hafta da değiştirilebilirdi.

Add Task butonuna tıkladığımızda çıkan pop-up ekranından saatleri ve günleri ayarlayabildiğimiz bir kısım eklenebilirdi.

Day componentinin tablo yapısı daha kullanışlı olabilirdi ve Day sayfasından da direkt olarak task silinebilirdi.

TypeScript daha etkin kullanılabilirdi.

Projeyi `npm start` ile çalıştırabiliriz.

## Docker

Build =>
```sh
docker build -t task-app:dev .
```

Run =>
```sh
docker run --name my-task-planner -t -d -p 
3000:3000 task-app:dev
```

