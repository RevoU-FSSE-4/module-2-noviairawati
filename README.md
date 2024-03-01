Hello, This assignment for week 4
Theme: "Melody Music Course"
I use _HTML, CSS and Javascript_ to built the website.
HTML Version: _HTML5_

## Version Control

### Creating Branches

1. In any Git project, you can see all branches by writing the following command in the command line:
   git branch

2. It's very easy to create a new branch, just write the following command in the command line:
   git checkout "name of new Branch"

### Commiting Changes

git add <files>
git commit -m <message>

### Merging Code

git checkout other_branch
git cherry-pick changed_branch

## Structure Website:

1. HTML Semantic Structure
2. CSS File (style.css)
3. Javascript File (script.js)
4. Readme File for documentation (README.md)
5. Images File (IMG) & (Assets)

## Semantic Element:

I use Semantic Element to built the website

1. Header
2. Main
3. Footer

## Source

1. [color hunt](https://colorhunt.co/)
2. [Free Pik](https://www.freepik.com)

## Deployment Process, Setting Domain & Subdomain

There are few steps in Deployment Process: Setting Up DNS and Make subdomain to Netlify.

### Setting Up DNS
The following are the steps for setting DNS for the first time buying a domain. However, this is not the deployment that I used for assignments in week 4.

1. Previously, select the project on Netlify that will be used according to the domain that has been purchased at Niaga Hoster. Then, Inside of the Netlify dashboard, navigate to your domain settings and click “Add Domain Management”

![2](/Assets/image-54.png)

2. Enter the name of your domain and click “Verify”.

![3](/Assets/image-70.png)

3. After that has finished, click on the options menu next to your new domain and choose “Set up Netlify DNS”.

![3](/Assets/image-55.png)

![4](/Assets/image-56.png)

4. Follow the steps here by choosing “Verify”, then “Add Domain”, and “Continue”. Then when you get to the screen about domain name servers, copy those name servers.

![6](/Assets/image-58.png)

![7](/Assets/image-59.png)

5. Then, in the dashboard where you bought your domain (mine is Namecheap), set the DNS to custom DNS and add the DNS names from Netlify.

![8](/Assets/image-63.png)

![9](/Assets/image-64.png)

6. Then, in the dashboard where you bought your domain (Niaga Hoster), set the DNS to custom DNS and add the DNS names from Netlify > Click "Change" > and Then Click "Save".

![10](/Assets/image-61.png)

![11](/Assets/image-65.png)

![12](/Assets/image-66.png)

![13](/Assets/image-67.png)

7. Click "Done" in Netlify

![14](/Assets/image-68.png)

8. After that, you may need to wait a few minutes for the settings to propogate, you should eventually see the “Netlify DNS” tag associated with your domain name.

![15](/Assets/image-71.png)

![16](/Assets/image-72.png)

![17](/Assets/image-73.png)

### Auto Deployement on Github with Netlify

1. Add New Site

![1](/Assets/image.png)

![2](/Assets/image-1.png)

2. Link to Your GitHub (or supported version-control tool of choice), then Clicking "Import An Existing Project"

![3](/Assets/image-2.png)

![4](/Assets/image-3.png)

3. Authorize Netlify It's time to authorized your Netlify and GitHub to connect each other. Clicking the "Authorized"

![5](/Assets/image-4.png)

4. Select Your Repo Now that you've connected Netlify and GitHub, you can see a list of your Git repos. Choose the repo you’d like to deploy from the list.

![7](/Assets/image-5.png)

5. Configure Your Settings click the "Deploying" button to continue.

![8](/Assets/image-6.png)

![9](/Assets/image-7.png)

6. Build Your Site Now it's time to sit back and relax. You did your part; let Netlify take care of the rest. It'll only take a minute.

![10](/Assets/image-8.png)

7. All Done Once the build completes, your site is live! Head to the overview and you can see the URL of your newly published site.

![11](/Assets/image-9.png)

![12](/Assets/image-10.png)

8. Netlify automatically generated a name for your site. Let's update that by visiting the settings tab and clicking "Change site name":

![13](/Assets/image-11.png)

![14](/Assets/image-12.png)

![15](/Assets/image-13.png)

![16](/Assets/image-14.png)

Here's my deploy on Netlify:
[melody music course](https://melodymusiccourse.netlify.app/)

![17](/Assets/image-16.png)

### How to Make Subdomain

Now I want to create a subdomain with the results of deploying my project assignment. This subdomain is the address I will use in my Assignment.

1. Select the website on Netlify that you want to create a subdomain for.

![1](/Assets/image-15.png)

2. Select "Domain Management"

![2](/Assets/image-17.png)

3. Select "Add Domain"

![3](/Assets/image-18.png)

4. Write the name "Subdomain" and select "Verify"

![4](/Assets/image-20.png)

![5](/Assets/image-19.png)

5. Your subdomain has been successfully created.

![6](/Assets/image-21.png)

Check the link of your subdomain : [Melodymusciccourse](http://melodymusiccourse.noviairawati.site/)

Thank You :)