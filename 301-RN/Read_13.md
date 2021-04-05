# Update/Delete

## Client/server architecture

![img](https://carta.readthedocs.io/en/1.0/_static/carta_intro_serverClient.png)

> *Client send a request to server using HTTP or HTTPS and the server response with a proper answer using HTTP or HTTPS depiinding on the request protocol.*
> **HTTP**, **HTTPS**: stands for Hyper Text Transfer Protocol, Secure is for the "S", husing the HTML is the best way to contact with this cind of protocols.
> ### Client side:

**`<form>`:** that defines how the data is sent, and uses:

**action:** defines where the data gets sent and redirected.

**method:** defines how data is sent by `POST`, `GET`, `PUT`, `DELETE`.

**GET**
> It is used to ask the server to send back a given resource: *Hey server, I want to get this resource*.
**POST**
> It is used to talk to the server when asking for a response with the data provided in the HTTP request: *Hey server, send me an appropriate result.*



#### Viewing HTTP requests

![images](images/http.jpg)

 - HTTP requests are never displayed to the user (if you want to see them, you need to use tools such as the Firefox Network Monitor or the Chrome Developer Tools). As an example, your form data will be shown as follows in the Chrome Network tab. 

> ### Server side:
> the server receives data and convert it to list of key/value pairs.

## Sending files:

![img](https://www.dignited.com/wp-content/uploads/2018/06/best-file-sharing-storage-tools.jpg)

> **sending files over *HTTP, HTTPS* is considerd as a spicial case the reason is that HTTP is a text protocol and files are binary data.**
> **and the best way to deale with it as by encrybting the file; use POST and use the `<input type="file">`.**
