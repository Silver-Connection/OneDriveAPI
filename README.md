# OneDriveAPI
OneDrive API in C#

Microsoft offers their own SDK for communicating with OneDrive. I personally find that one to be too cumbersome and complex to use. I've therefore written my own library which communicates with the OneDrive API. It allows for file uploading (up to 10 GB), file downloading, modifications, retrieving listings and much more. It is still in alpha stage though, so feel free to use this code whereever you see fit, but don't expect a 100% fine working piece of code. I'm using this library for a couple of months now to upload large amounts of files to OneDrive on a steady base and didn't encounter any issues anymore with this version. Feel free to reach out in case you find something that you believe could be improved.

## Available via NuGet
You can also pull this API in as a NuGet package by adding the following NuGet repository to Visual Studio:
http://nuget.koenzomers.nl/nuget or running the following line from the NuGet Package Manager Console in Visual Studio:

Install-Package -Id KoenZomers.OneDrive.Api -Source https://nuget.koenzomers.nl/NuGet

## Version History

1.1.0.0 - July 10, 2015

- Fixed incorrect conflictBehavior tag when using Resumable Upload. It is now set to always overwrite the file if it already exists on OneDrive.

## Feedback

Feedback is very welcome. If you believe something is not working well or could be improved, feel free to drop me an e-mail.

Koen Zomers
mail@koenzomers.nl