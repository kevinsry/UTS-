# UTS-
UTS sistem administrasi server

## 				** UTS Sistem administrasi server**

**Kevin Surya Diansyah**

**1202190028**

**IT02-01**


```markdown
1.	Download ISO Installer windows server 2022
```

```markdown
-	Dengan mengklik link yang telah tersedia pada soal uts, maka akan dibawa ke link tersebut dengan tampilan seperti dibawah ini :
```

![1](https://user-images.githubusercontent.com/89094789/143685148-f632a573-9ec6-4732-b049-c0e3cdcc521b.PNG)

```markdown
-	Pilih download the ISO kemudian ikutin sesuai step by stepnya. Jangan lupa centang "yes" kemudian continue
```

![2](https://user-images.githubusercontent.com/89094789/143685229-35e9a2fc-ce2a-4eaf-b57f-10f246b7c114.PNG)


```markdown
-	Pilih bahasa yang diinginkan dan klik download
```
![bahasa](https://user-images.githubusercontent.com/89094789/143685343-619f0d6a-6c40-41a5-8f59-8d163b3371ca.PNG)

```markdown
2.	cara instal
```

```markdown
-	Open VirtualBox and go to the “machine – New” Menu :
```

![2](https://user-images.githubusercontent.com/89094789/143685517-b3579989-13d9-469d-b3ad-60431f15dd6a.PNG)


```markdown
- Enter the name of the machine and type of system to use
```
![WhatsApp Image 2021-11-27 at 21 58 39](https://user-images.githubusercontent.com/89094789/143686566-6a67d3cc-11d5-44ef-9881-06204a4d6e17.jpeg)

```markdown
- Define ram, create the disk defining type and size
```

![2 1](https://user-images.githubusercontent.com/89094789/143686655-3b15bd50-541a-4603-a491-511ce9b3143e.PNG)

```markdown
- Go to the machine configuration and in the “Network” section set “Bridge adapter”
```

![2 2](https://user-images.githubusercontent.com/89094789/143686788-2a1ba883-bafb-4775-9ef7-09ee9fd645cf.PNG)

```markdown
- Click on “Start” and select the ISO downloaded
```
![2 3](https://user-images.githubusercontent.com/89094789/143687016-b8b0ba96-a73b-44fd-bd2d-2bb226e9edce.PNG)
![2 4](https://user-images.githubusercontent.com/89094789/143687022-5dc67981-7908-4e52-8d4e-de5ab17d3d5b.PNG)

```markdown
- Click on “Start” and the Windows Server 2022 installation wizard will load
```

![2 5](https://user-images.githubusercontent.com/89094789/143686977-84e06962-b75c-49b2-82d3-71bfab1b15d1.jpeg)

```markdown
- Click on “Install now”
```
![2 6](https://user-images.githubusercontent.com/89094789/143687211-4535184a-2eaa-449c-872e-a6e2b85c41b7.PNG)

```markdown
- Enter the license (if you have on) and then define the edition to use, Accept the license and then proceed with the installation of Windows Server 2022
```
![2 1](https://user-images.githubusercontent.com/89094789/143687305-00c9e767-805f-4394-bd05-9eeb0b3da895.PNG)

![2 2](https://user-images.githubusercontent.com/89094789/143687309-c92f13fd-afec-44be-95ff-a7ee017e0b8b.PNG)

![2 3](https://user-images.githubusercontent.com/89094789/143687317-f5b2f306-a02d-4753-a51b-ef516f9d4f68.PNG)

![2 4](https://user-images.githubusercontent.com/89094789/143687326-14ccccdc-ddbb-4b73-98fa-4277272c32d9.PNG)


```markdown
- The system will reboot to complete the process
```
![2 1](https://user-images.githubusercontent.com/89094789/143687444-cd09f0db-07eb-4318-9468-c517b20617bf.PNG)

![2 2](https://user-images.githubusercontent.com/89094789/143687449-55cec6dd-4c59-4a9e-8612-e5781d5bf7aa.PNG)

```markdown
- Enter the administrator password
```
![3](https://user-images.githubusercontent.com/89094789/143687504-8e95f9cd-c078-4d74-badb-0fcf6060f9bf.PNG)

```markdown
- Go the menu “Devices – Insert Guest Additions CD Image” , From the Explorer run this and follow the steps pf the wizard. Reboot the machine
```
![1](https://user-images.githubusercontent.com/89094789/143687749-5fae7993-6cb6-4a68-b873-93600e649c8b.png)

![2](https://user-images.githubusercontent.com/89094789/143687752-d072f223-6486-497b-b2fc-45eff625c11b.PNG)

![3](https://user-images.githubusercontent.com/89094789/143687761-69b094b1-419a-4915-8be0-41016318ccb2.PNG)

![4](https://user-images.githubusercontent.com/89094789/143687763-c18074c4-123e-428e-b4c9-b43b106f9472.PNG)

![5](https://user-images.githubusercontent.com/89094789/143687765-8f0ddffa-66fb-4788-aba3-ebce49b2ffa8.PNG)

```markdown
- Run “winver” to validate the installed edition of Windows Server
```

![image](https://user-images.githubusercontent.com/62064492/143058074-ab6a8d6f-8421-433e-afd9-3d1873a4123c.png)

```markdown
A. Instalasi Active Directory Domain Services
```

```markdown
- Sebelum melakukan instalasi , kita merubah nama computer terlebih dahulu dengan masuk ke windows powershell. Kemudian ketikkan “rename-computer -Newname Server2022”
```

![image](https://user-images.githubusercontent.com/62064492/143058230-c8536ec9-1ac0-4789-9b63-0b592839313d.png)

```markdown
- Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”.
```
![image](https://user-images.githubusercontent.com/62064492/143058338-b6117d81-8479-4860-94f9-f4371a630f72.png)

```markdown
- Pilih opsi “Role-based or feature-based installation”. Lalu “Next”
```

![image](https://user-images.githubusercontent.com/62064492/143058402-8450dfce-0c8f-4b3a-b14d-4da3691fd439.png)

```markdown
- Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”
```

![image](https://user-images.githubusercontent.com/62064492/143058537-a5d1dc41-1d55-405d-8fea-ce5335b89c61.png)

```markdown
- Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”.
```
![image](https://user-images.githubusercontent.com/62064492/143058626-b950b867-673b-4be0-8644-571d715e5c91.png)

```markdown
- Kemudian centang kotak “Group Policy Management” dan tekan tombol “Next”.
```

![image](https://user-images.githubusercontent.com/62064492/143058709-2e1fce7f-3cf7-4203-9ec1-5aa1600f3e04.png)

```markdown
- Selanjunya klik “Next” lagi.
```
![image](https://user-images.githubusercontent.com/62064492/143058812-7cc2737b-c66a-4d48-bce0-ebab12dfc834.png)

```markdown
- Klik “Install”.
```

![image](https://user-images.githubusercontent.com/62064492/143058927-66049ec4-f165-4ffa-a11f-d3ba398feaef.png)

```markdown
- Tunggu hingga proses instalasi selesai kemudian melakukan konfigurasi ADDS
```
![image](https://user-images.githubusercontent.com/62064492/143059056-4b3a2b2c-c4a3-43c7-bf11-a974412b383e.png)



```markdown
B. Instalasi DNS server
```

```markdown
- Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama. 
```

![image](https://user-images.githubusercontent.com/62064492/143059169-bc75ab5c-54dc-474f-b9b1-a809f8547103.png)



```markdown
C. Instalasi Net Framework 3.5
```

```markdown
- Centang “.NET Framework 3.5 features”
```

![image](https://user-images.githubusercontent.com/62064492/143059289-ca4aa9b0-e658-445c-b6eb-7b01ddb2192e.png)

```markdown
- Selanjunya klik “Next” lagi.
```

![image](https://user-images.githubusercontent.com/62064492/143059414-e40ac556-cbd2-4192-8fc6-3459d68decd8.png)

```markdown
- Selanjutnya klik “Install”.
```
![image](https://user-images.githubusercontent.com/62064492/143059520-231922be-4757-4c00-bf38-e89398e48da4.png)

```markdown
- Tunggu hingga proses instalasi selesai
```

![image](https://user-images.githubusercontent.com/62064492/143059642-a839d8d3-231c-4f1e-8a5a-fe37c474cb02.png)

```markdown
- Apabila mengalami eror seperti gambar dibawah ini, solusi dari saya melakukan windows update ke versi 21H1 yang dimana sudah include instalasi .NET Framework 3.5 
```
![image](https://user-images.githubusercontent.com/62064492/143059738-7efa2ff3-83f2-42e2-9f84-578082f27a29.png)

```markdown
- Dan Ketika saya ngecek ulang, sudah ke install

```
![image](https://user-images.githubusercontent.com/62064492/143059913-323cfebb-8baa-4d03-b6c4-e78dad592013.png)


```markdown
**Promote Server to a Domain Controller**
```

```markdown
- Seting ke ip static menggunakan cmd, ketik sconfig
```

![image](https://user-images.githubusercontent.com/62064492/143060040-3187b4bc-c2ef-442e-924a-36ef3cebe5a4.png)

![image](https://user-images.githubusercontent.com/62064492/143060060-92f95ebf-600c-4c5e-8df0-fea1880b923f.png)

```markdown
- Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan.
```

![image](https://user-images.githubusercontent.com/62064492/143060278-638d7a68-2f9f-4e0a-ac89-b449a6b29bc1.png)

```markdown
- Klik “Promote this server to a domain controller untuk konfigurasi ADDS
```
![image](https://user-images.githubusercontent.com/62064492/143060623-08bef976-72e9-424a-a31b-668860218189.png)

```markdown
- Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “Aim.com”
```
![image](https://user-images.githubusercontent.com/62064492/143062005-9155bdfa-ea42-4cb3-91ec-3e4b0072998a.png)

```markdown
- Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password.
```

![image](https://user-images.githubusercontent.com/62064492/143062084-1c336f87-a714-444b-badc-ce385c59e73c.png)

```markdown
- Lewati bagian DNS Options, lalu klik “Next”.
```

![image](https://user-images.githubusercontent.com/62064492/143064837-a5dd8d07-d77c-4cbe-a96d-eb6b2a120c6e.png)

```markdown
- Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan.
```
![image](https://user-images.githubusercontent.com/62064492/143062175-cfc66680-5ce8-40e5-b879-13239b76cd74.png)

```markdown
- Lewati bagian Paths, klik “Next”.
```

![image](https://user-images.githubusercontent.com/62064492/143062494-2c7a08ce-49f3-40db-ad12-4490ec112b99.png)

```markdown
- Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”.
```
![image](https://user-images.githubusercontent.com/62064492/143062586-0f8f8e3b-1a2b-4546-9779-f70238828d1a.png)

```markdown
- Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan.
```
![image](https://user-images.githubusercontent.com/62064492/143062766-88e37beb-aa83-4b18-ba2d-b20fec2e6c8f.png)

```markdown
- Tunggu hingga proses instalasi selesai.
```

![image](https://user-images.githubusercontent.com/62064492/143062877-c7a3a0e7-cdd8-404a-9ac2-a4204c5bfd46.png)

```markdown
- Setelah login dengan Active Directory Domain Controller, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS yang disukai
```

![image](https://user-images.githubusercontent.com/62064492/143063183-bdb4c10d-c204-41d6-b2b5-67c1ccd33348.png)
