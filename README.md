# ST_StreamLabs-Water-Flow
This is an unofficial Classic SmartThings interface to the StreamLabs Water Flow Meter [Streamlabs Water Monitor](https://www.streamlabswater.com/). It allows SmartThings to be able to control the StreamLabs Home/Away status as well as providing StreamLabs flow alerts as SmartThings water leaks.
## Getting Started
The StreamLabs API runs in the "cloud"; for SmartThings to interrogate cloud interfaces, it requires two pieces: both a Device Handler and a Service Manager (a special kind of SmartApp). You will need to obtain the groovy source code for both from GitHub and install them into the SmartThings IDE.
### Obtaining Source Code & IDE Installation
You can either use the traditional cut-and-paste method or integration with GitHub to provide the source code to the SmartThings IDE. The Device Handler is called "" and the Service Manager/SmartApp is called ""StreamLabs Water Flow SM"". If using GitHub integration, you will need the following information: Owner=windsurfer99, Name=ST_StreamLabs-Water-Flow, Branch=master.  For additional information on these standard SmartThings practices, some suggested documentation includes:
 - [FAQ: An Overview of Using Custom Code in SmartThings (SmartThings Classic)](https://community.smartthings.com/t/faq-an-overview-of-using-custom-code-in-smartthings-smartthings-classic/16772)
 - [FAQ: GitHub Integration How to Add and Update from Repositories](https://community.smartthings.com/t/faq-github-integration-how-to-add-and-update-from-repositories/39046)
### Getting an API Key
You will need to request an API key for your account from StreamLabs. As of my initial creation, the API was free but there are indications that there may be a cost in the future. Follow the instructions on the [StreamLabs Getting Started](https://developer.streamlabswater.com/docs/getting-started.html) page to request your API key. My interface only supports the API key mode of authentication (OAUTH2 is not currently supported), so make sure you follow the steps to request that.
### Install API Key
After installing the Device Handler and Service Manager and then receiving the key from StreamLabs, it must be entered into the Service Manager.  In the SmartThings IDE, select the newly installed "StreamLabs Water Flow SM" on the "My SmartApps" page. Select "App Settings" in upper right of the  page. Expand "Settings" and enter "api_key" in the name box (if not already populated) and the provided key in the value box. select "Update' on the bottom of the page.
### Phone App Installation


### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

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

* Hat tip to anyone whose code was used
* Inspiration
* etc
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc2OTAzNTYyMiwtMTI0MjEyNDc3MywtMT
g1Mjc2NjQ3LC00ODk3MjgzNzUsNjM5ODYyNzEzLDY2NDg4MzE0
NywtMTExNjg0MTI3NSwxMTM0NTc2NDcxLDY0MTI3MTE2Ml19
-->