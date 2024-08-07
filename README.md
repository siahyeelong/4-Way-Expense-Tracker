# 4-Way Expense Tracker

## Overview

This project is a Google Sheets template designed to help you track expenses shared among 4 individuals. It's perfect for travel groups, or any scenario where expenses are shared equally. The tracker automatically calculates the total expenses and each individual's share, and tabulates how much each individual owes another, simplifying the process of managing and splitting costs.

## Features

- **Automated Calculations**: Automatically calculates the total expenses and each person's share.
- **Easy Data Entry**: Easily log your expenses through Google Forms.
- **Real-Time Updates**: Syncs in real-time as you and your group members update expenses.
- **Visualised Summary and Analysis**: Provides a summary of expenses and individual I-owe-you-s for each user, visualised in a simple dashboard on Google Sheets

## Getting Started

Try it out for yourself and customise to your own needs!

### Prerequisites

- Google Sheets
- Google Forms
- Some editting of Google Sheets and Forms parameters to suit your needs (optional)

### Installation

1. **Download the Template**:
    - [Click here to download the template](https://docs.google.com/spreadsheets/d/15ttgRjgiWdQmu7Egyv8HJ95B2In5nUXaaEr7PBNWDzQ/edit?usp=sharing)

2. **Make a Copy**:
    - Open the Google Sheets link.
    - Go to `File > Make a copy` to save it to your Google Drive.

### Usage

1. **Setup the linked Google Form**:
    - Open your copied Google Sheets file.
    - Go to `Tools > Create a new form`
    - Copy the format of [this form](https://forms.gle/BkiWC1d6bmXpugGb6) 
        - Ensure the questions are the exact same
        - Instead of user1, user2, etc., change it to your preferred names (optional)
    - Go to your Sheets, and delete the `Raw Data` worksheet. Rename your linked Form Responses worksheet as `Raw Data`
    - You might have to go to the `All SGD` worksheet and click in to Cell A1, where it'll fix the reference automatically
    > You have now linked the Form to the Sheet. Any responses logged in the Form will be saved and reflected in the Sheet. 

2. **Configure Names**:
    > We now need to configure the names accordingly. Skip this step if you kept the user names as user1, user2, etc.

    - Go to the Sheet
    - Under the `parameters` worksheet, edit the names of your users accordingly. They must be the same as what you have indicated in the Form
    - Under the `main` worksheet, change the colours of your users' dropdown selector in Cell I4


3. **Customise to Your Application**:
    > The Sheet I have made originally calculates the currency and converts to SGD automatically. Since it is unlikely I spend S$18k, I made the rule such that if the logged expense is above 18k, assume that the value was logged in VND. 

    > You may customise your rules, either by creating a new question in your Form to ask for the currency, or take the date of departure as when you should convert your currency back to SGD
    - To customise, go to `All SGD` and edit the formula in Cell A1 to your own application

4. **Share with Your Buddies!**
    - In the Sheet, click Share, and allow anyone to edit. Send the link to your friends! 
        - Hide any worksheet and lock any cells if required
    - In the Form, click Send, and share the form to your friends!
