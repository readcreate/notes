# quick start

link to this page: [v.ht/akstart](https://v.ht/akstart)

## ubuntu install codes

Install Zoom, Chromium, GDebi, TeamViewer

```
sudo apt install snapd

sudo snap install zoom-client

sudo snap install chromium

# above installs snapd, zoom, chromium
```

Ubuntu Software app might also work to install Chromium and Zoom.

This fix might be needed for Zoom to work right, especially on Ubuntu 22.04:

```
zoom --disable-gpu-sandbox
# from https://askubuntu.com/questions/1405245/zoom-client-crashes-on-ubuntu-studio-22-04-lts
```

```
sudo add-apt-repository main
sudo add-apt-repository universe
sudo add-apt-repository restricted
sudo add-apt-repository multiverse  


sudo apt install gdebi

# above adds gdebi (might need to run 
sudo apt --fix-broken install 
and then try again)
```



Download <a href="https://www.teamviewer.com/en-us/download/linux/" target="_blank">TeamViewer</a>

Right-click on TeamViewer installer -> Open With Other Application -> GDebi Package Installer

Might also work for TeamViewer and other debian files: 

```
cd Downloads
sudo dpkg -i teamviewer_15.32.3_amd64.deb
```

## links to open

<a href="https://mail.yahoo.com" target="_blank">Yahoo Mail</a>

<a href="http://outlook.office.com" target="_blank">Outlook</a>

<a href="http://calendar.google.com" target="_blank">Google Calendar</a>

<a href="http://web.whatsapp.com" target="_blank">WhatsApp Web</a>

<a href="http://messages.google.com/web" target="_blank">Messages Android/Google</a>

[Magical - Text Expander](https://chrome.google.com/webstore/detail/magical-text-expansion/iibninhmiggehlcdolcilmhacighjamp)

[MGHIHP D2L](https://mghinstitute.desire2learn.com/d2l/login)

[Microsoft Teams](teams.microsoft.com)

## references to open

[Anshul RPubs page](https://rpubs.com/anshulkumar)

[MGHIHP HE902 textbook](https://bookdown.org/anshul302/HE902-MGHIHP-Spring2020/)

[MGHIHP HE930 textbook](https://bookdown.org/anshul302/paml/)

[MGHIHP HE802 textbook](https://bookdown.org/anshul302/HE802-MGHIHP-Spring2020/)

[Unsupervised Machine Learning Clustering Tutorial in Google Colab](http://tinyurl.com/AnshulCluster1)

Kumar, A., Edwards, R. A., & Walker, L. (2021, August 17). The application of predictive analytics to identify at-risk students in health professions education. Not yet a peer reviewed publication. Pre-print: https://doi.org/10.35542/osf.io/wtuv6  or https://arxiv.org/abs/2108.07709

Kumar A. Edwards RA. AdaptiveLearnalytics: Adaptive Predictive Learning Analytic Tools. 2021. https://github.com/readcreate/AdaptiveLearnalytics.

[Mental health first aid and first response notes](https://github.com/readcreate/notes/blob/main/MentalHealthFirstAid.md)

## ubuntu occasionally useful code

Check RAM: `sudo lshw -c memory`
