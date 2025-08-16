Link: https://www.w3schools.com/python/python_virtualenv.asp

Run:  python -m venv JobScraper

    Result: 
        creates new folder :  JObScraper
        contents : Include, Lib, Scripts, pyvenv.cfg


Activate environment
    source JobScraper/Scripts/activate
        


  note: 
    bash uses /
    powershell uses \


error:
    (jobScraper doesn't show at beginnig of bath)

        try: which python -- shows where the things(pip) are pointing

            result
               venv not active -  C:/Python39/python
               venv active - /c/Users/YourName/JobScraper/Scripts/python

        try -- which pip : shows where the pip is pointing

            
        answer:
            bash requires the source key word
                source JobScraper/Scripts/activate
            
            powershell : 
                JobScraper/Scripts/activate

Other Keywords

    which pythpn : shows where            
