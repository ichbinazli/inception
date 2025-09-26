## 🎯 Projenin Amacı
- Hazır imajlar kullanmadan, **kendi Dockerfile’larını yazarak** Docker öğrenmek.  
- **Çoklu container** ortamını Docker Compose ile yönetmek.  
- Bir **WordPress sitesi** kurup bunu veritabanı ve web sunucusuyla çalışır hale getirmek.  
- **Volume, network ve SSL sertifikaları** ile uğraşmak.  

---

## 📦 Servisler
Zorunlu olarak kurulması gereken servisler:
- **Nginx** → Web sunucusu + **SSL (self-signed sertifika)**  
- **WordPress + PHP-FPM** → Dinamik CMS  
- **MariaDB** → WordPress veritabanı  

---

## 🔑 Kurallar
- Her servis için **kendi Dockerfile’ını** yazmalısın.  
- **Volume** kullanımı zorunlu → veriler container silinince kaybolmamalı.  
- Servisler **Docker network** üzerinden haberleşmeli.  
- **SSL** desteği zorunlu.  

---

## 🛠️ Öğreneceklerin
- Sıfırdan **Docker imajı oluşturma**.  
- **Container networking** yönetimi.  
- **Volume** kullanarak verilerin kalıcı hale getirilmesi.  
- **docker-compose** ile servis orkestrasyonu.  
- **DevOps ve sistem yönetimi** temelleri.  

---

## 📚 Çalışma Adımları
1. Nginx, WordPress ve MariaDB için `Dockerfile` oluştur.  
2. `docker-compose.yml` dosyasında servisleri, network ve volume yapılarını tanımla.  
3. **Self-signed SSL sertifikası** üret.  
4. Tüm sistemi çalıştır:  
   ```bash
   docker-compose up --build



https://excalidraw.com/#json=_iZilylimVhkxzUYKu8Re,pJuHgVGlNgwlmWhakwJ_0Q
