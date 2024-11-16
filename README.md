## Final Checkpoint

### Task
Deploy a website about things that you built and deployed on Netlify. The deployment must be auto deploy from your project’s main branch using GitHub Action. Your portfolio website can be accessed by custom domain (example domain : http://budoacademy.rf.gd/ ) and documented on a readme with screenshots. Readme must explain about:  

1. Netlify Sign up process & connect Netlify to your Github project  
2. Auto Deployment on Github with Netlify  
3. How to connect your custom domain and DNS  

### Applied

## Web Description

Step by step about deploying and Applying custom domain to the website:

1. Deploy it on Netlify  
    a. First, we need to go to netlify.com  
        <p align="center">
          <img src="assets read.me/1.png" height="100">
        </p>  
    b. Second, we need to log in with GitHub Account (You can login with another method if you are not using GitHub)  
        <p align="center">  
          <img src="assets read.me/2.png" height="100">
        </p>  
    c. Third, when you already on the dashboard, click on the "Add New Site" button and select "Import an existing project"  
        <p align="center">  
          <img src="assets read.me/3.png" height="100">
        </p>  
    d. After that, choose from where you want to import the project (i choose GitHub beacuse my project is on GitHub)  
        <p align="center">  
          <img src="assets read.me/4.png" height="100">
        </p>  
    e. Then, you can choose in which organization your project is (Mine is not on my account, but in oragnization)  
        <p align="center">  
          <img src="assets read.me/5.png" height="100">
        </p>  
    f. After that, select your desired repo to deploy  
        <p align="center">  
          <img src="assets read.me/6.png" height="100">
        </p>  
    g. Then, you can fill all the information needed and click on the "Deploy (yoursitename)" button (but actually, you just need to fill the "Site name" and left the rest)  
        <p align="center">  
          <img src="assets read.me/7.png" height="100">
        </p>  
        <p align="center">
          <img src="assets read.me/8.png" height="100">
        </p>  
    h. After that, wait for netlify to build your site (it could take a couple minute to an hour).
      
    i. Your site already deployed.

2. Buy your custom domain  

    You already deploy your site to the internet, now everyone can acces your site throught its domain. Congratulations! But as you can see, even though your second-level domain has a name that you already wanted, but the top-level domain is still not quite you wanted (it has netlify.app). So you need to buy a custom domain first.

    a. First, go to your desired domain registrar (i'm prefered niagahoster.co.id because Kak Mahi told me to do so)  
        <p align="center">
          <img src="assets read.me/9.png" height="100">
        </p> 
    b. Second, log in with your google account (you can log in with another method)  
        <p align="center">  
          <img src="assets read.me/10.png." height="100">
        </p> 
    c. Third, on the dashboard, got to "Domains" tab and click "Get a New Domain"
        <p align="center">  
          <img src="assets read.me/11.png" height="100">
        </p> 
    d. After that, you can type your desired custom domain on the search bar. You can also choose the top-level domain based on your desire (or your budget). Scroll down to see its availibility.  
        <p align="center">  
          <img src="assets read.me/12.png" height="100">
        </p> 
    e. Then, continue with the payment  
        <p align="center">  
          <img src="assets read.me/13.png" height="100">
        </p> 
        <p align="center">
          <img src="assets read.me/14.png" height="100">
        </p> 
    f. You can see your purchased domain at the "Domain Portofolio" tab section. Congratulations, you are already purchased a custom domain based on you desire (or budget)  
        <p align="center">  
          <img src="assets read.me/15.png" height="100">
        </p> 
3. Applying custom domain to your site on Netlify  

    Yes, you already your custom domain, but that doesn't mean its already applied to your site. You need to connect it between your site and your custom domain.

    a. First, go back to your domain registrar and on the "Domain" tab section, click on the "Domain protofolio" and choose your already purchased custom domain then click "Manage"
        <p align="center">  
          <img src="assets read.me/16.png" height="100">
        </p>  
    b. Then, click on the "DNS / Nameservers" tab section and look for the "Nameservers" and remember that 4 Nameservers (Just kidding, you don't need to remember it, you can just copy-paste it)  
        <p align="center">
          <img src="assets read.me/17.png" height="100">
        </p> 
    c. After that, go back to netlify.com and choose your deployed site
        
    d. Then, on the site overview, look for "Set up your site" section, and click on the "Set up a custom domain ->"
         
    e. After that, fill the input text with the custom domain you already bought and click verify. If its available, then you can click on "Add domain"
         
    f. Then, in your dployed site, go to "Domains" tab section and look for "Name servers" section. Copy all 4 of the Name Servers (that looks like dns.p09.nsone.net)
        
    g. Last, go back to your domain registrar. click on the "Change Nameservers" and paste it the Name Servers from the netlify. Don't forget to click "Save" button.

    h. Finally, your website already deployed and has it custom domain. (You can check your site on netlify.com and need to wait a couple minute to an hours for the servers to be connected)
        <p align="center">  
          <img src="assets read.me/18.png" height="100">
        </p> 
    You can see the result of my deployed website with custom domain at http://toko-action-figure.shop
        
