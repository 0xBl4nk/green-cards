# What is it
**green-cards** is basically a python project that creates a sequence of commits on random dates to generate green squares on github.

# How it works
Basically it works by generating random dates within a set time interval and uses the **os** library to commit the date generated within the commits.yml file and at the same time be committed to that date through the ```--date``` parameter, after all commits it push for the repository.

Note: Despite being compatible with Windows systems, performance drops significantly when used on that system.

# How to use
You must **fork the repository** and **clone from your profile**, after that just run:
```bash
python app.py
```

# Results
<img src="https://i.imgur.com/JuONa2m.png">
