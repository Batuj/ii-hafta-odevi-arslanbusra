# II Hafta (6-7 Haziran) Ödevleri 

## 6 Haziran Ödevleri:
- [ ] Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)
- [ ] [Git and GitHub with Briana Swift](https://www.youtube.com/playlist?list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4) Youtube Listesi incelensin. (11 Video)
- [ ] Merge pull request
    - [ ] Create a merge commit
    - [ ] Squash and merge 
    - [ ] Rebase and merge altında ne fark var (Ödev)
- [ ] issue ve #pull request de id ler neden artıyor farklı sekmeler olmasına rağmen?
- [ ] [Ramp up on Git and GitHub](https://lab.github.com/githubtraining/paths/ramp-up-on-git-and-github) (ödev)
- [ ] Aspnetboilerplate ve yan ürünler araştırması. [AspNet Boilerplate - Web Application Framework](https://aspnetboilerplate.com/)
- [ ] hackerRank.com --> [30 Days Of Code](https://www.hackerrank.com/domains/tutorials/30-days-of-code)


## 7 Haziran Ödevleri:
- [ ] Razor Pages Nedir?
- [ ] 4 Farklı Projede Yapılacak *Change Authentication* :
  - [ ] No Authentication
  - [ ] Individual User Account
  - [ ] Work or School Accounts
  - [ ] Windows Authentication seçili projeler oluşturulmalı
- [ ] Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? [Ders Akışındaki 6. Madde'yi inceleyin.] ( araştırma ödev verildi ).
- [ ] c# json serialize / deserialize
- [ ] MVC vs MVVM
   - [ ] MVP vs MVW vs MVU Pattern arasındaki farkı araştır
   - [ ] Model-View-Update (MVU) nedir?

**GitFlow;**

Gitflow, zamanlanmış bir yayın döngüsü olan projeler için idealdir. Farklı dallara çok özel roller atar ve nasıl ve ne zaman etkileşime girmeleri gerektiğini tanımlar.

Master ve develop olmak üzere iki ana koldan oluşur.Master üretimin bitmiş halini develop ise geliştirme amaçlı kullanılan bir daldır. Bir de ana koldan kopmadan ve master ile birleşmeden gelişen özellik dalları bulunur. Bunlar; feature,hotfix,release olarak tanımlanır.

**Feature;** özellik dalları, gelecek sürümler için yeni özellikler geliştirmek için kullanılır. Gelişmeden ayrılabilir ve gelişmek üzere birleşmelidir.

**Hotfix;** düzeltme dalları, master'ın istenmeyen durumuna derhal davranmak için gereklidir. Ustadan ayrılabilir ve ustaya karışıp gelişmelidir.

**Release;** sürüm dalları yeni bir üretim sürümünün hazırlanmasını sağlar. Birçok küçük hatanın düzeltilmesine ve bir sürüm için meta verilerin hazırlanmasına izin verir. Gelişimden ayrılabilir ve ustalaşıp gelişmelidir.

**Git flow ne zaman kullanılır?**

--Sürekli dağıtımda veya sürümlerde çalışılması sebebi ile sürüm tabanlı bir yazılım geliştirme için uygundur.

--Geliştirme kolu geliştirme ve proje arasında güvenlik sağlar.

![gitflow](https://user-images.githubusercontent.com/66273342/84819643-04410200-b021-11ea-8ffc-27736bbdb723.PNG)



**Github Flow;**

GitHub Flow, dağıtımların düzenli olarak yapıldığı ekipleri ve projeleri destekleyen hafif, dallanan bir iş akışıdır. Bir proje üzerinde çalışırken, herhangi bir zamanda devam eden bir dizi farklı özellik veya fikre sahip olunabilir. 

Github ile yeni bir **branch** oluşturulması gerekir. Böylelikle yapılacak değişiklikler ana dalı etkilememiş olur. Oluşturulan bu şubeye bir dosya eklendiğinde, düzenlendiğinde veya silindiğinde, **commit** işlemi gerçekleştirilmiş olup ve bunlar şubeye eklenmiştir. Oluşturduğumuz bu fikri paylaşmak veya fikir almak için ise **pull request** oluşturarak geri bildirimler de alınabilir. Paylaşılan yenilik tartışılır, test edilir, incelenir. Bunun sonrasında değişiklikler ana dal ile **merge** edilir yani birleştirilir.

**Github Flow ne zaman kullanılır?**

--Sürekli Entegrasyon ve sürekli dağıtım için uygundur.

--Küçük iyileştirme yapılacağı zaman kullanılabilir.

![githubflow](https://user-images.githubusercontent.com/66273342/84819563-e70c3380-b020-11ea-878d-f26312471823.PNG)
