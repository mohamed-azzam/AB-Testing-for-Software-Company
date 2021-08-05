# Introduction

A/B Testing for new Homepage layout for software company

# Scenario Description

Let's say that you're working for a fictional productivity software company that is looking for ways to increase the number of people who pay for their software. The way that the software is currently set up, users can download and use the software free of charge, for a 7-day trial. After the end of the trial, users are required to pay for a license to continue using the software.

One idea that the company wants to try is to change the layout of the homepage to emphasize more prominently and higher up on the page that there is a 7-day trial available for the company's software. The current fear is that some potential users are missing out on using the software because of a lack of awareness of the trial period. If more people download the software and use it in the trial period, the hope is that this entices more people to make a purchase after seeing what the software can do.

In this case study, you'll go through steps for planning out an experiment to test the new homepage. You will start by constructing a user funnel and deciding on metrics to track. You'll also perform experiment sizing to see how long it should be run. Afterwards, you'll be given some data collected for the experiment, perform statistical tests to analyze the results, and come to conclusions regarding how effective the new homepage changes were for bringing in more users.

# A Funnel

Now, we should think about the activities that a user will take on the site that are relevant to measuring our objective. This path or funnel will help us figure out how we will create experimental condition groups and which metrics we'll need to track to measure the experiment's effect. To help you construct the funnel, here's some information about the way the company's website is structured, and how the software induces users to purchase a license.

The company's website has five main sections:

1. the homepage;
2. a section with additional information, gallery, and examples;
3. a page for users to download the software;
4. a page for users to purchase a license; and
5. a support sub-site with documentation and FAQs for the software.

For the software itself, the website requires that users create an account in order to download the software program. The program is usable freely for seven days after download. When the trial period is hit, the program will bring up a dialog box that takes the user to the license page. After purchasing a license, the user will receive a unique code associated with their site account. This code can then be used with the program to register it with that user, and the program can be used thereafter without issue.

Using the information above, fill in your responses to the questions below regarding the construction of a user funnel, then check on the next page for my thoughts.



# Deciding on Metrics

## Invariant Metrics

I use number of cookies that hit the homepage as Invariant Metrics

## Evaluation Metrics

I use Count-based metrics at other parts of the process seem like natural choices: the number of times the software was downloaded and the number of licenses purchased are exactly what we want to change with the new homepage.

# Experiment Sizing

Recent history shows that there are about 3250 unique visitors per day, with slightly more visitors on Friday through Monday, than the rest of the week. There are about 520 software downloads per day (a (520/3250=.16) rate) and about 65 licenses purchased each day (a (65/3250=.02) rate).

**Detecting change in downloads**

Let's say that we want to detect an increase of 50 downloads per day (up to 570 per day, or a .175 rate). How many days of data would we need to collect in order to get enough visitors to detect this new rate at an overall 5% Type I error rate and at 80% power?



**Detecting change in licenses**

What if we wanted to detect an increase of 10 license purchases per day (up to 75 per day, or a .023 rate). How many days of data would we need to collect in order to get enough visitors to detect this new rate at an overall 5% Type I error rate and at 80% power?

> Note that the solution for experiment size exist in Notebook



# Conclusions

Despite the fact that statistical significance wasn't obtained for the number of licenses purchased, the new homepage appeared to have a strong effect on the number of downloads made. Based on our goals, this seems enough to suggest replacing the old homepage with the new homepage. Establishing whether there was a significant increase in the number of license purchases, either through the rate or the increase in the number of homepage visits, will need to wait for further experiments or data collection.