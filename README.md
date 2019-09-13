# Instabase Challenge @ HackMIT

**Prize: $1000 to split amongst the team**

Instabase is a data processing platform providing services such as OCR, text extraction, natural language processing, and text classification. We're awarding $1,000 to the team that demonstrates the best use of our platform to solve a problem! More specifically, solve a problem using our platform to do:

* Optical Character Recognition
* Natural Language Processing
* Clustering and classification
* Information extraction and web scraping
* Python Scripting

Visit instabase.com/hackmit for more information about our API.


## Getting Started

### 1. Create an account on Instabase

In order to create an account, go to [our registration page](https://www.instabase.com/account/register?use_token=true) and use the following token:

```
hack-mit-2019
```

### 2. Create a new workspace/repository

A repository/workplace is a place to hold all of your code. Create one by clicking "New Workspace" in the Workspaces menu.

[INSERT IMAGE HERE]

### Need Help?

We will be here all weekend to help with your projects! Come by our booth in the area, or contact our mentor at aaron@instabase.com

You can also text our mentor at (860) 805-0050


## What can I do with Instabase?

Below is a list of just a few of the capabilities of Instabase. Follow the link for each one and copy the folder into your workspace/repository. Each project has a README detailing the capabilities and how to run that project.

For a full list of features and documentation, visit our [documentation site](https://www.instabase.com/docs/index.html).

### Extract Text from Images (OCR)



### Extract Information from Documents/Images

### Create a Document Classifier

### Automate with Custom Scripting

### Jupyter Notebooks


## Common FAQ

### How do I use Instabase via API?

Most Instabase functionality is available through both UI and and API. In order to use Instabase via API (for instance, to run Flows, OCR, NLP, read and write files, etc...), create an access token by doing the following:

1. Go to [instabase.com](https://www.instabase.com/)
2. Click the IB Icon (to access the main menu)
3. Hover over "Help"
4. Click "Developer SDK"
5. Click "New Application" in the top right of the screen
6. Enter a name and description for your project
7. Copy the Access Token generated for your project

Details for API calls can be found [in our documentation](https://www.instabase.com/docs/content/apis/index.html)

The Access Token is passed via a header in your HTTP requests. For instance, in Python this might look like the following:

```python
url = 'some/url/to/instabase/features'
headers = {
  'Authorization': 'Bearer {0}'.format(my_access_token),
  'Instabase-API-Args': json.dumps(my_api_arguments)
}
resp = requests.post(url, headers=headers).json()
```
