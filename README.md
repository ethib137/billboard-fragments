# Billboard Fragment Collection Contributor

> NOTICE: This project has been moved to the [Demo Fragment Collections](https://github.com/lfrsales/demo-fragment-collections) project.

A set of chart fragments for Liferay 7.3+ based on [billboard.js](https://naver.github.io/billboard.js/).

## Usage

After deploying billboard fragments the charts can be found on any content page under Section Builder > Billboard Fragments. 

![billboard-fragments](/images/billboard-fragments.png)

The data can be modified through the fragments configuration. It includes default data that can be used to understand the basic format of the data that is required. If you run into an issue reset the configuration and try again.

![data-configuration](/images/configuration.png)

### Custom Colors

The colors used in the charts can be customized by adding the following css:

```
.bb-color-pattern {
  background-image: url("#00c73c;#fa7171;#2ad0ff;#7294ce;#e3e448;#cc7e6e;#fb6ccf;#c98dff;#4aea99;#bbbbbb;");
}
```

## How to Build and Deploy to Liferay

### Build it
` $ ./gradlew build `
The jar file will be in `build/libs/com.liferay.fragment.collection.contributor.billboard-1.0.0.jar`.

### Deploy to Liferay
` $ ./gradlew deploy -Pauto.deploy.dir="/path/to/liferay/deploy"`

## Issues & Questions Welcome