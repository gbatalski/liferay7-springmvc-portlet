# liferay7-springmvc-portlet
Example Spring MVC Portlet that can be deployed as a WAB on Liferay 7

In this project you find an example of:
* Maven build using maven-bundle-plugin
* DIDN'T APPROVE: Maven profile for deploying to a local Liferay instance (requires maven properties to be set up as described [GitHub](https://dev.liferay.com/develop/tutorials/-/knowledge_base/6-2/deploying-liferay-plugins-with-maven) )
* Spring WebMVC Portlet version 4.2.6
* An Autowired Service class
* Apache Commons Logger
* A call to the Liferay API (using PortalUtil) to retrieve the current authenticated user
* A model object to pass to the view
* Thymeleaf 3.0.0 as a template engine configured to use message bundles
* Enabled action url generation for request routing from thymeleaf forms

## Tested on
* Liferay 7 GA1 Tomcat bundle, running on Java 8 Linux Kernel 4.6.0 with HSQL
