# spring-restful
# Building a RESTful Web Service with Spring

This guide explains how to build a RESTful web service using the Spring framework.

## Overview

The service accepts HTTP GET requests at `http://localhost:8080/greeting` and responds with a JSON representation of a greeting. The greeting can be customized with an optional `name` parameter in the query string.

## Steps

1.  **Project Setup:** Use Spring Initializr to set up the project.
2.  **Resource Representation:** Create a resource representation class to model the greeting.
3.  **Resource Controller:** Build a resource controller to handle HTTP requests.
4.  **Run the Service:** Run the service and test it by visiting `http://localhost:8080/greeting`.
5.  **Executable JAR:** Build an executable JAR file for easy deployment.