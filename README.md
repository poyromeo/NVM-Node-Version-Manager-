<h4>NVM-Node-Version-Manager</p>
<p>React Projelerinde her proje için node js sürümü hataları karşımıza çıkıyor. Bunu önlemek için nvm yani Node-Version-Manager kullanarak her proje için node js sürümünü değiştirip uyumlu olanı kullanabiliriz.</p>

<h4>GEREKLİ ADIMLAR</p>
<ol>
  <li>Bilgisayardaki node js sürümünü kaldırın.</li>
  <li>Root yolu C:\Users\userName\AppData\Roaming içinde olan npm ve npm-cashe dosyalarını silin</li>
  <li>https://github.com/coreybutler/nvm-windows/releases bu adresten nvm-setup.exe dosyasını indirip kurun</li>
  <li>Kullanacağız node js sürümlerini PowerShell'de ayrı ayrı "nvm install [version]" olacak şekilde indirin.</li>
  <li>PowerShell'de nvm list diyerek node js sürümlerinizi görebilirsiniz.</li>
  <li>Projenizde hangi node js sürümü geçerliyse terminalde çalıştırmadan önce nvm use [version] yaparak default node js sürümüzü belirleyin.</li>
  <li>Bundan sonra projenizi çalıştırıp devam edebilirsiniz.</li>
</ol>
<br/>
<h4>NVM-Node-Version-Manager</p>
<p>In React Projects, node js version errors occur for each project. To prevent this, we can use nvm, that is, Node-Version-Manager, to change the node js version for each project and use the compatible one.</p>
<h4>REQUIRED STEPS</p>
<be>
   <li>Uninstall the node js version on the computer.</li>
   <li>Delete the npm and npm-cashe files whose root path is in C:\Users\userName\AppData\Roaming</li>
   <li>Download and install the nvm-setup.exe file from https://github.com/coreybutler/nvm-windows/releases</li>
   <li>Download the node js versions we will use separately as "nvm install [version]" in PowerShell.</li>
   <li>You can see your node js versions by clicking nvm list in PowerShell.</li>
   <li>Whichever node js version is valid in your project, determine your default node js version by doing nvm use [version] before running it in the terminal.</li>
   <li>After that you can run your project and continue.</li>
</ol>
