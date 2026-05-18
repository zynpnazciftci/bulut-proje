<img width="2000" height="1500" alt="localhost" src="https://github.com/user-attachments/assets/7dc514b2-fca6-4468-8ef4-793a678264be" />

## Kişisel Web Sayfası Vize Ödevi

- Proje Adı: Docker ile Kişisel Web Sayfası Dağıtımı
- Öğrenci Adı:Zeynep Naz ÇİFTÇİ
- Kullanılan Teknolojiler: HTML5, CSS3, Docker, Nginx
- Projenin Kısa Açıklaması: Bu proje, HTML ve CSS kullanılarak geliştirilen kişisel tanıtım sayfamın, Docker konteyner teknolojisi ve Nginx web sunucusu kullanılarak yerel ortamda (localhost) izole bir şekilde çalıştırılması projesidir.

## Docker Çalıştırma Komutları
Projenin ayağa kaldırılması için sırasıyla aşağıdaki komutlar kullanılmıştır:
1. İmajı derleme komutu:
docker build --no-cache -t webproje .

2.Konteyneri çalıştırma komutu:
docker run -d -p 8080:80 webproje
