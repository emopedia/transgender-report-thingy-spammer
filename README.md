# missouri spammer
Spam those transphobes out of existence! but what?
Fake Information provided by [Fake Name Generator](https://www.fakenamegenerator.com "Fake Name Generator")

## Instructions

pip install -r requirements.txt

1. Configure the options you need at the top of the file.
```python
# Change configuration settings here.
config.zipFile = "fake-details.zip"
config.fakeDetailsFile = "FakeNameGenerator.com-100000-UK,US,AUS,CAN.csv"
config.fakeDetailsLength = 100000
config.multiThreading = True
config.multiThreads = 50
```
2. Add your target URL to the variable in the make_request function.
```python
url = 'https://ago.mo.gov/file-a-complaint/transgender-center-concerns'
```
3. Configure your web request in the data variable. Use the person variable created from the fakePerson class to get your fake information (see example).
```python
data = {'Textbox-1':person.firstName,'Textbox-2':person.lastName,'Textbox-3':person.address,'Textbox-4':person.city,'Textbox-5':person.postal,'Textbox-6':person.email,'Textbox-7':person.telephone,'Textarea-1':person.username}

```
5. Run and Attack!
