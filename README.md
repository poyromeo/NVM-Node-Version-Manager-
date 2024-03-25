<h4>NVM-Node-Version-Manager</p>
<p>React Projelerinde her proje için node js sürümü hataları karşımıza çıkıyor. Bunu önlemek için nvm yani Node-Version-Manager kullanarak her proje için node js sürümünü değiştirip uyumlu olanı kullanabiliriz.</p>

<h4>#GEREKLİ ADIMLAR</p>
<ol>
  <li>Bilgisayardaki node js sürümünü kaldırın.</li>
  <li>Root yolu C:\Users\userName\AppData\Roaming içinde olan npm ve npm-cashe dosyalarını silin</li>
  <li>https://github.com/coreybutler/nvm-windows/releases bu adresten nvm-setup.exe dosyasını indirip kurun</li>
  <li>Kullanacağız node js sürümlerini PowerShell'de ayrı ayrı "nvm install [version]" olacak şekilde indirin.</li>
  <li>PowerShell'de nvm list diyerek node js sürümlerinizi görebilirsiniz.</li>
  <li>Projenizde hangi node js sürümü geçerliyse terminalde çalıştırmadan önce nvm use [version] yaparak default node js sürümüzü belirleyin.</li>
  <li>Bundan sonra projenizi çalıştırıp devam edebilirsiniz.</li>
</ol>
