#StarsToRain
Simple Python script that exports all Github Stars for a given user into an HTML file importable by Raindrop.io

##Installation and Usage
Start by cloning this repo.

This Python script uses [PyGitHub](https://github.com/PyGithub/PyGithub) as a dependency for calling the Github API v3, so first run the following command line:

```bash
sudo pip install -r requirements.txt
```

Once all dependencies are fetched you can use the script:

```bash
python starsToRain.py
```

You will be prompted for your Github username and password.
Once the script is done doing the export you'll find your html file into the output directory.
