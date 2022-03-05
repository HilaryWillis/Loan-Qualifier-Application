# Loan Qualifier Application

The Loan Qualifier Application is a command line application that allows a User to enter pertinent information that is used to determine which home loans the User qualifies for. The Users information is compared against a csv file that contains qualifying specifications for multiple mortgage lenders. The output will result in providing the User the names of the companies that will lend them a mortgage. From here, the User will be given the option to save the csv file to their computer. 

---

## Technologies 

This application is written in [Python](https://www.python.org/downloads/), using the [Fire](https://google.github.io/python-fire/guide/) and [Questionary](https://questionary.readthedocs.io/en/stable/index.html) libraries. The Fire library helps convert Python code into a command line interface. Questionary allows the command line interface to query python code for user input. It is highly recommended that the User open the Loan Qualifier Application folder in the [Visual Stuido Code](https://code.visualstudio.com/) integrated development environment. User can use their terminal or command line for this application on MAC/OS, Windows or Linux Operating Systems.


---

## Installation Guide

To use the program, save the Loan Qualifier Application folder on your computer. Open the folder in VS Code from the command line/terminal. Your VS Code Explorer should look like this:

![Explorer Menu](Loan_Qualifier_Application\images\1.png)


---

## Usage

Open the 'app.py' file and run the code in the Integrated Terminal, and press the play button:

![Open app.py file](Loan_Qualifier_Application\images\2.png)

When prompted to 'Enter a file path to a rate-sheet (.csv)', enter the relative file path of the daily_rate_sheet.csv as shown in the example:

![File path to rate-sheet](Loan_Qualifier_Application\images\3.png)

Answer the following prompts based on the Users personal parameters. Select 'yes' if you want to save the list of qualifying lenders to your computer.

![User personal information](Loan_Qualifier_Application\images\4.png)

---

## Contributors

Created in collaboration with [UW Fintech Bootcamp](https://bootcamp.uw.edu/fintech/landing/?s=Google-Brand&pkw=uw%20fintech%20bootcamp&pcrid=479786454877&pmt=e&utm_source=google&utm_medium=cpc&utm_campaign=GGL%7CUNIVERSITY-OF-WASHINGTON%7CSEM%7CFINTECH%7C-%7COFL%7CTIER-1%7CALL%7CBRD%7CEXACT%7CCore%7CBootcamp&utm_term=uw%20fintech%20bootcamp&s=google&k=uw%20fintech%20bootcamp&utm_adgroupid=111256639914&utm_locationphysicalms=9033287&utm_matchtype=e&utm_network=g&utm_device=c&utm_content=479786454877&utm_placement=&gclid=CjwKCAiAjoeRBhAJEiwAYY3nDNkjpiKxjHHO5N4PKK9hstUoeNYRj_FBbnhxwV9tZaaxThPlOQqBERoC8UYQAvD_BwE&gclsrc=aw.ds) and Hilary Willis, hilarywillis@gmail.com. You can find Hilary on LinkedIn at: (https://www.linkedin.com/in/hilary-willis-a230121)

---

## License

MIT License

Copyright (c) [2022] [Hilary Willis]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

