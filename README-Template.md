# Tutorial how to build Mobile App using Qt to find Closest Facility
# Lab4 

In case of emergency, time have a big role in saving lives. Therefore, it is important to identify the closest healthy facility from the incident which takes the minim time to arrive. Prerequisites To develop this Two_Maps screen, we have to have Esri online account and installed Esri App Studio on our machine. 

## Get your ESRI Online account and Login into ESRI App Studio

Once you get your account, go to https://www.esri.com/landing-pages/appstudio download and install Esri App Studio. Qt Creator (AppStudio for ArcGIS) will be installed with Esri App Studio. 

### Developing Closest Hospital finder Mobile app

1. Once the necessary applications are installed open Esri app studio on your desktop and login.
2. On upper right corner click New App On the Tittle give name of your app, I gave mine “Closest Hospital”. 
3. From the three items under Sample, select Closest Facility, then click on create to create your app. 
4. Now go to the gallery and refresh. You should see your newly created app in ESRI App studio gallery. 
5. Now we created a mobile app with one map screen with the default buttons and basemap (Topographic basemap).
6. After the app is created, we have to customize and make necessary changes according to our requirement.
The first step is to change the center of the map to our area of interest, in my case, I am working for Tacoma city. Therefore, my center is point is X= -122.44, Y= 47.25.
Before changing the viewpoint lets us as change the Basemap and Spatial reference

### Change teh base Map and Spatial reference



```
Map { BasemapStreets {}

```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc

