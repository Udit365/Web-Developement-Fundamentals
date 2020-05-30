# HTML Forms

Forms are used to gather input from the user that can be stored in a database for future use or, can be sent via emails.

Such input forms can be created using HTML and the data generated can then be submitted to a PHP scipt for processing.

## Flow of Data for Forms

The following flow chart shows, how the user data flows when they submit a form.

## Creating a HTML Form

The `<form>` tags is used to create the HTML forms.

Just like many other tags, the `<form>` tag also take up several arguments in its opening tag.

The below example shows an opening `<form>` tag, taking up 3 important arguments :

```html
<form name="employement" action="send.php" method="POST">
  .... .... ....
</form>
```

In the above example :

- `name="employement"` sets up the form name as "_Eployment_"
- `action="send.php"` sends the user input data to a PHP file named "_Send.php_" for processing.
- `method="POST"` sets the method as `GET`

## `POST` Vs. `GET` Method

The HTTP protocol facilitates the communication between the client and server.

This communication can be facilitated by two methods of data transmissions, i.e., `POST` and `GET` method.

- The `GET` method requests data from a specified resource.
- The `POST` method submits data to be processed to a specified resource.

### `GET` Method

Name/Value pairs are sent to the URL string.

_For Example :_

```
send.php?fname=Jhon&lname=Smith
```

#### Properties of `GET` requests :

- Can be cached
- Remain in browse history
- Should only be used to retrieve data
- Have length restrictions
- Shouldn't be used for sensitive data, viz., passwords
- Can be bookmarked

### `POST` Method

Sends the name/value pairs in the HTTP message body.

_For Example :_

```
send.php HTTP/1.1
Host: website.com
fname=Jhon&lname=Smith
```

#### Properties of `POST` methods :

- No restrictions on data length
- Can't be bookmarked
- Don't remain in browse history
- Requests are never cached.
