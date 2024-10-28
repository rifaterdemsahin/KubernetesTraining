Environment: Pilot
Bu projeyi danışmanlık sürecine uygun hale getirip, 16 haftalık ve 8 haftalık zaman çizelgesi çıkararak organize edebiliriz. Bu plan, iki kişi için olacak ve her hafta belirli görevler tamamlanacak şekilde hazırlanmıştır. Ellerinde yapılacak görevlerle birlikte, hands-on egzersizler odaklıdır. İki kişi bu görevleri birlikte tamamlayacak şekilde çalışabilir.

16 Haftalık Plan
1. Hafta:
Kubernetes Cluster Kurulumu:
5 node'lu (1 Master + 4 Worker Node) Kubernetes cluster kurulumu.
Kurulum dokümantasyonu ve konfigurasyonların kaydedilmesi.
2. Hafta:
Namespace’ler Oluşturulması:
"test" ve "production" namespace'lerinin oluşturulması.
3. Hafta:
Rollerin Oluşturulması:
Junior ve senior grupları için gerekli rollerin oluşturulması ve namespace’ler üzerindeki yetkilendirmelerinin yapılması.
4. Hafta:
Ingress Controller Kurulumu:
Seçilen bir ingress controller’ın kurulumu ve konfigurasyonu (nginx, traefik, haproxy vb.).
5. Hafta:
Node Toleration ve Affinity Kurulumu:
Production için sadece belirli node’larda pod’ların schedule edilmesi için node affiniy ve taint kuralları belirleme.
6. Hafta:
WordPress ve MySQL Deploymanı - Test Ortamı:
WordPress ve MySQL'in test namespace'inde deploy edilmesi, servis ve persistent volume tanımları.
7. Hafta:
WordPress ve MySQL Deploymanı - Production Ortamı:
Production namespace'inde WordPress ve MySQL deploymanlarının yapılması.
8. Hafta:
Ingress Tanımları:
Test ve production ortamlarındaki WordPress uygulamaları için ingress tanımlarının yapılması (testblog.example.com, companyblog.example.com).
9. Hafta:
Deployment Konfigürasyonu:
"ozgurozturknet/k8s:v1" deployment'ının production ortamına kurulması ve probe’ların eklenmesi.
10. Hafta:
Load Balancer Kurulumu:
Deployment için load balancer tipi bir servis ile dış dünyaya erişim sağlanması.
11. Hafta:
Deployment Scale ve Güncelleme İşlemleri:
Deployment replikalarının önce 3’e indirilmesi, ardından 10’a çıkarılması ve v2 imajıyla güncellenmesi.
12. Hafta:
Fluentd DaemonSet Deploymanı:
Fluentd uygulamasının bir daemonset olarak cluster'a deploy edilmesi.
13. Hafta:
MongoDB StatefulSet Deploymanı:
2 node'lu MongoDB cluster’ının statefulset olarak deploy edilmesi ve çalıştığının doğrulanması.
14. Hafta:
Service Account ve Pod İlişkilendirilmesi:
Okuma ve listeleme yetkilerine sahip bir service account oluşturulması ve bu account’a bağlı bir pod deploy edilmesi. Pod üzerinden cluster'daki pod'ların listelenmesi.
15. Hafta:
Pod Tahliye ve Node İzolasyonu:
Bir worker node üzerindeki tüm podların tahliye edilmesi ve bu node’a yeni podların schedule edilememesinin sağlanması.
16. Hafta:
Sonuçlandırma ve İnceleme:
Tüm sürecin gözden geçirilmesi, eksikliklerin düzeltilmesi ve projenin tamamlanması.

8 Haftalık Hızlandırılmış Plan
1. Hafta:
Kubernetes Cluster Kurulumu ve Namespace’ler:
5 node'lu cluster kurulumu ve "test" ve "production" namespace'lerinin oluşturulması.
2. Hafta:
Roller ve Yetkilendirme:
Junior ve senior grupları için rollerin oluşturulması ve namespace yetkilerinin yapılandırılması.
3. Hafta:
Ingress Controller Kurulumu ve Node Affinity:
Ingress controller kurulumu ve node affinity ile production için özel node belirlenmesi.
4. Hafta:
WordPress ve MySQL Deploymanı:
Hem test hem production namespace’lerinde WordPress ve MySQL deploy edilmesi, persistent volume ve servis konfigürasyonlarının yapılması.
5. Hafta:
Ingress ve Uygulama Tanımlamaları:
Ingress kurulumlarının yapılması (testblog.example.com, companyblog.example.com) ve resource limitlerin belirlenmesi.
6. Hafta:
Production Deployment:
"ozgurozturknet/k8s:v1" deployment'ının kurulması, probe’ların eklenmesi ve load balancer’ın tanımlanması.
7. Hafta:
Scale ve Güncelleme İşlemleri:
Deployment replikalarının azaltılıp artırılması ve imaj güncellemelerinin yapılması. Fluentd daemonset deploy edilmesi.
8. Hafta:
MongoDB Cluster ve Service Account:
MongoDB statefulset ve service account deploy edilmesi, pod tahliyesi ve node izolasyonu işlemlerinin tamamlanması.

Bu plan, hands-on egzersizlerle iki kişilik bir ekip için organize edilmiştir ve belirli sürelerde tamamlanabilir.


