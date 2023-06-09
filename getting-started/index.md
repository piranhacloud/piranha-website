# Getting Started

## Quickstart using Piranha Web Profile

Download a version of Piranha Web Profile from [Maven Central](https://repo1.maven.org/maven2/cloud/piranha/dist/piranha-dist-webprofile/).

Run your web application using:

```shell
java -jar piranha-webprofile-X.Y.Z.jar --war-file your-webapplication.war
```

## What other distributions can I use?

The short answer is that it depends on your needs. 

If you want to embed Piranha into your application you can pick Piranha Embedded to start embedding Piranha directly into your own application. If you are looking for a lean REST runtime then you should pick Piranha Core Profile. 

If you are looking for a traditional Servlet container, similar to Tomcat and Jetty, then Piranha Server or Piranha Servlet are your best bet. For hosting multiple web applications on the same distribution use Piranha Server. For hosting just a single web application pick Piranha Servlet.

If you are wondering what Jakarta EE or Micro Profile specification each of the distribution supports see our [Jakarta EE / Micro Profile matrix](matrix.md)

## Distribution specific documentation

* [Piranha Core Profile](../core-profile/index.md)
* [Piranha Embedded](../embedded/index.md)
* [Piranha Servlet](../servlet/index.md)
* [Piranha Server](../server/index.md)
* [Piranha Web Profile](../web-profile/index.md)

## Maven Plugin documentation

If you are using Maven and want to use our convenient Maven plugin for a quick iterative development cycle, see the [Piranha Maven plugin documentation](../maven/piranha-maven-plugin/index.html).

## Extending Piranha

You can extend the capability of a Piranha distribution by means of extensions.

## How do you run Piranha in a container

Piranha images are available from the [GitHub container registry](https://github.com/orgs/piranhacloud/packages), on a best effort basis. If you desire commercially supported images we suggest you contact our commercial partner [OmniFish](https://omnifish.ee/contact-us/).

[Up](../)
