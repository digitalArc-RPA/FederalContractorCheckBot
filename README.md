# FederalContractorCheckBot

## Getting Started

This is a Repository for showcasing the federal contractor check bot, configured to be deployable on any machine using UiPath.

## Software Used in the Process

+ UiPath Studio
+ MS Outlook
+ IExplorer

## Built With

+ UiPath Studio

## Description 

This bot processes the DUNS number check, by listening to emails containing the number(s) with "Federal Contractor Check" in the email's subject.
It navigates to SAM and FAPIIS websites and scrapes the data required, storing it into files and returns an email to the sender with a specific DUNS number company's summary and zipped file package.

### Authors

Pijus Mackevicius, digitalArc
