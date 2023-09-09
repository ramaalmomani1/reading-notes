# API Integration

---

#### Review API Server Build

1. Explain the different between a query string parameter and a path parameter.

> Path Parameter:
Path parameters are part of the URL's path or route.
They are used to specify a specific resource or entity within the URL.
Path parameters are typically enclosed in curly braces {} within the URL structure.
They are often used to identify a unique record.


> Query String Parameter:
Query string parameters are appended to the end of a URL after a question mark (?) and separated by ampersands (&).
They are used for filtering, sorting, or providing additional data to a resource.
Query string parameters are not used to directly identify a specific resource but rather to modify the behavior or results of a request.

2. What would our API URL with a path id parameter be given the following information:

- Domain: http://our-site.com
- v3
- model name: stuff
- id: things

> http://our-site.com/api/v3/stuff/things



3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

>  Dynamic API like a versatile tool that helps our computer talk to other computers to get information. It follows a set of rules:
Getting Data: We can ask it to fetch data.
What Data: We can specify what kind of data we want.
How We Get Data: It gives us the data in a computer-friendly format.
Adding and Changing Data: We can also tell it to add new data or update existing data.
Organized Data: It provides data neatly.

---

#### Review Auth Server Build

1. Describe how you would use middleware to implement basic and bearer auth.

> Basic Auth Middleware checks your username and password when you log in.
Bearer Auth Middleware checks your special token to let you access certain areas.

2. Describe the handshake necessary to implement OAuth.

> OAuth is like logging in with Google or GitHub.
You log in, give permission, and get a special token for future access.

3. Describe how Role Based Access Control works to a non-technical friend.

> RBAC is like giving different keys to different people.
Each key only opens specific rooms, so you can't access places you shouldn't.
