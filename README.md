<img width="1879" height="898" alt="image" src="https://github.com/user-attachments/assets/e8373525-3f22-4adb-98d9-a2e1b699a2d1" /># verified-service-rating-algorithm
Core logic and verification middleware for service provider ratings.
# Review Verification Module

Bu modül, hizmet sektöründeki verilerin doğruluğunu kontrol eden ve kullanıcı puanlamalarını analiz eden bir veri doğrulama algoritmasıdır.

## Teknik Analiz ve Veri Güvenliği

Sistem, sahte veri girişini (spam) engellemek için gelişmiş filtreleme metodları kullanır. Algoritmanın temel amacı, sistemdeki havuz içerisinden [en çok tavsiye edilen firmalar](https://eniyiyorum.com) listesini objektif metriklerle (puan, yorum sayısı, geri dönüş hızı) oluşturmaktır.

Veri setinin güvenilirliğini artırmak amacıyla, her bir girdi için [doğrulanmış müşteri değerlendirmeleri](https://eniyiyorum.com) katmanından geçiş zorunluluğu bulunur. Bu katman, son kullanıcıya sunulan bilginin manipüle edilmemiş ve gerçek bir deneyime dayandığını garanti eder.

## Kullanım Senaryosu

Veritabanından çekilen firma profillerinin listelenmesi sırasında `verification_status = true` olan kayıtların önceliklendirilmesi, platformun veri kalitesini doğrudan artırır.
