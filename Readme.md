## Moonpy.

This should answer a short list of basic questions:

* **It is a library use to read Hermajest US navy moon data and present the following Parameters according to the provided location**
* **Moon Altitude**
* **Sun and Moon Altitude and Azimuth,**
* **Lag Time, Moon Illumination, DAZ(Difference in Sun and Moon Azimuth)**  

You likely have the answer to many of these questions in your head and have discussed them with your team. It's helpful to write them down for people who find your repository. Not only will it be easier for developers to know how to fork the project or become involved with the project, but it will be easy for non-coders to understand what the code is designed to do, and how they, too, can become involved.

**Big Questions:** 

* What is Moonpy?
* How does Moonpy work?
* Who uses Moonpy?
* What is Moonpy goal?
* How can your organization benefit from using Moonpy?

## Instructions for how to develop, use, and test the moonpy.

This should answer the question: **How do I get this project to work on my machine? How can I develop for this project?** We find it works really well if you follow a two-step approach to develop the content for this section: first, help someone setup the site who has never done it before, and then write down the exact instructions. Next, ask someone to follow those instructions and see if you’ve missed anything.

Important: If relevant code changes, it’s important to test to ensure these instructions continue to work. We also recommend separating the sections for using a project versus developing for it. (More detailed instructions are located [in our guidelines](https://pages.18f.gov/open-source-program/pages/maintainer_guidelines/#usage-documentation) for writing documentation for users, contributors, and developers.)

**Example:** The README for analytics.usa.gov contains detailed instructions for [developing the site](https://github.com/18f/analytics.usa.gov#setup) and [deploying the site](https://github.com/18f/analytics.usa.gov#deploying-to-staging-18f-specific).  

## Instructions for how people can help.

We [explicitly welcome outside contributors](https://github.com/18F/open-source-policy/blob/master/practice.md#accepting-contributions-from-the-public). It’s important to explicitly state how they can help and what they can help with. This part of the website should answer the question: **How can outside contributors become involved?** We include a [CONTRIBUTING.md](https://github.com/18F/open-source-policy/blob/master/CONTRIBUTING.md) file in each repo, which outlines the following:

* If there are any additional setup steps specific for development.
* Whether there are explicit Instructions for running tests before contributions are accepted.
* If there are any requirements for contribution, if any, e.g.
  * A Contributor License Agreement
    * CLAHub
    * http://oss-watch.ac.uk/resources/cla
    * http://contributoragreements.org/
  * If commits should be squashed
  * Whether there is a specific coding style to adhere to. (Generally contributors will match what they see within a project.)
* Whether potential contributors should ask before they make significant changes.
* Whether work-in-progress pull requests are ok.
* What 18F's [Code of Conduct](https://github.com/18F/code-of-conduct) states

**Example:** The README for Midas contains a section called “[How you can help.](https://github.com/18f/midas#how-you-can-help)” What we really like about this section is that it doesn’t assume helpers are developers and lists ways for lots of different people to contribute. (Our [guide to welcoming non-coders to hackathons](https://18f.gsa.gov/2015/04/03/how-to-welcome-new-coders-to-a-civic-hackathon/) also contains many suggestions for ways to involve people with different skillsets.)

We also recommend reading Midas’ [Contributor’s Guide](https://github.com/18F/midas/blob/dev/CONTRIBUTING.md), which orients new dev contributors and tells them the best ways to communicate with Midas’ dev team.

## List the licensing information for your project.

This part of the repo should answer the question: **What is the license for this project?** All 18F projects are developed in the international public domain whenever possible and contain a [LICENSE.md](https://github.com/18F/open-source-policy/blob/master/LICENSE.md) document, as well as a paragraph at the end of each README which contains information about the public domain. We post this information [in the README](https://github.com/18F/18f.gsa.gov#public-domain), so that users know the code can be adapted and reused, and so they can easily see this information instead of going to a second site.

### Include credit and licenses for embedded resources

If your project includes code or other resources (such as icons, fonts, or photos) from outside sources, your project's license description (in the README, LICENSE, and CONTRIBUTING files) should credit the authors of that work and include their license information.

It's polite to give full credit when reusing work, even if not legally required by the work's license, and this helps users who want to find the original source and use it.

We also have a legal responsibility to respect the licenses of work we use. When adapting or embedding outside work, check its license for instructions for complying with that license.

For example, see ["Licenses and attribution" in the U.S. Web Design Standards README](https://github.com/18F/web-design-standards#licenses-and-attribution). It starts with "A few parts of this project are not in the public domain", to prevent accidentally implying that all the project's files are in the public domain. It lists exceptions in this format: "The file *filename* is from *project name*, by *name of author* [or copyright *name of author*], under *name of license*." Then it has a section titled "The rest of this project is in the public domain", with the typical license information we put in READMEs. The project's [CONTRIBUTING file](https://github.com/18F/web-design-standards/blob/18f-pages-staging/CONTRIBUTING.md) includes the same sections. The [LICENSE file](https://github.com/18F/web-design-standards/blob/18f-pages-staging/LICENSE.md) has the same sections again, plus the full license text for some embedded works and our standard LICENSE information.

## List the contact information for your team as well as where to ask questions.

This part of the repo should make it easy for users to get in touch with the team developing the project. This is also where you should list any listservs, chat programs, or social media groups that have been created to keep contributors informed.

Any other information that you’d like to share with users can go in the Wiki section of your repository.




Install python 3.0 or above

dependencies:
Install dependencies "pip install -r requirements.txt"

Run Script:
cd to the directory where python file resides.
run "python moonPredictor.py"

Program Instructions:
if python script and data directory are in same dir then just enter directory name without inverted commas
Same as above for the outout directory
Date format should be "yy-mm-dd", it will search the date in the given data
Input Islamic Month with upper case, it will write it as it is in the pdf.
Same as above for Islamic year. 
A PDF will pop up in default browser and pdf with the same date you mentioned wth .pdf ext will be saved in output dir 

Program lines:
Input data directory(Drag and drop): moon data
Output file destination(Drag and drop): output
Date (yy-mm-dd): 2023-09-15
Islamic Month(Upper case): RABI-UL-AWWAL
Islamic year: 1445
Restarting...


Data format:
Replace the header with " year  h   cd conj  f wk   mon  day  set   Saz    age  Alt Maz  dz  Mag El  mset  lag   best  cat"
Remove irrelevent text written by publisher from all files
Make sure columns align correctly
Jiwani file is important because its conjuction time and moon age will be written on output file
If you want to add other city just rename it with correct format and place it in moon data directory.

