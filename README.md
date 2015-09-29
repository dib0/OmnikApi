# OmnikApi
Omnik Solar API in C#

I have done some research into the protocol used by Omnik and have created an API in C# on the Microsoft .NET 4.5 framework which can be used to query and parse the statistics from the Omnik device. Thanks to several great resources online and some investigation myself I managed to create the most rich and full open source API yet available on the internet for the Omnik Solar Inverters. Find the source code in this Github repository. The code is overly commented inline and contains a working sample console application, so for someone with some Microsoft .NET development skills it should be very easy to understand and implement in your own software. It supports both pulling data out an Omnik (actively connecting to it and requesting its statistics) as well as having the Omnik push data to us at an approximate 5 minute interval.

More information and to see it live being used in action against my solar panels, go to https://www.zomers.eu/domotics/solarpanels

## Download

For a directly executable version of this tool, [download it here](https://github.com/KoenZomers/OmnikApi/raw/master/Downloads/KoenZomers.Omnik.TestConsole.zip)

You can edit the values in the appSettings section in the KoenZomers.Omnik.TestConsole.exe.config file to have it connect to your Omnik Solar inverter.

## Feedback

Feel free to use it to suit your needs. If you believe something could be improved or need help, feel free to let me know.

Koen Zomers
mail@koenzomers.nl
