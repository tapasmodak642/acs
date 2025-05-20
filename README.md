# INSTALL GENIEACS OTOMATIS
This is autoinstall GenieACS 

# Usage
```
apt install git curl -y
```
```
git clone https://github.com/tapasmodak642/acs.git
```
```
cd acs
```
```
chmod +x install.sh && chmod +x darkmode.sh
```
```
chmod +x install-stb.sh
```
INSTALL GENIEACS DARK MODE v@1.2.13
```
bash darkmode.sh
```
INSTALL STB or RASBERRY v@1.2.13
```
bash install-stb.sh
```
INSTALL GENIEACS THEMA ORIGINAL v@1.2.13
```
bash install.sh
```

Baca terlebih dahulu !!!

#=== Script update GenieACS ====#

Config sebelumnya akan terhapus dan tergantikan oleh config baru

Yang akan diupdate, yaitu:

   • Admin >> Preset <br>
   • Admin >> Provosions <br>
   • Admin >> Virtual Parameter<br>
   • Admin >> Config<br>
   
#===Script/config tersebut akan terganti dengan yang baru ====#

যদি আপনার নিজস্ব কাস্টম কনফিগারেশন/স্ক্রিপ্ট থাকে,<br>
প্রথমে ব্যাকআপ নিন, তারপর আপডেটের পরে আপনার কাস্টম কনফিগারেশন অনুসারে আবার ম্যানুয়াল কনফিগারেশন করুন।<br>

ডিভাইস, ব্যবহারকারী, অনুমতি, এর ফলে প্রভাবিত হবে না<br>
যাদের কনফিগারেশনে ত্রুটি আছে, তাদের জন্য এই স্ক্রিপ্ট দিয়ে এটি মেরামত করা হবে<br>
আপনি এখনও পুনরুদ্ধার নির্বাচন করে পূর্ববর্তী কনফিগারেশনে ফিরে যেতে পারেন<br>
======= CARA RESTORE ========<br>
```
cd
```
```
```
sudo mongorestore --db=genieacs --drop genieacs-backup/genieacs
```
```
Genieacs port change

```
```
sudo nano /usr/bin/genieacs-ui
```
```
sudo systemctl enable genieacs-cwmp
sudo systemctl start genieacs-cwmp
sudo systemctl status genieacs-cwmp
sudo systemctl enable genieacs-nbi
sudo systemctl start genieacs-nbi
sudo systemctl status genieacs-nbi
sudo systemctl enable genieacs-fs
sudo systemctl start genieacs-fs
sudo systemctl status genieacs-fs
sudo systemctl enable genieacs-ui
sudo systemctl start genieacs-ui
sudo systemctl status genieacs-ui
```
