## Using virtualenv
> Instaling

```cmd
py -m pip install --user virtualenv
```
> Creating new env

```cmd
py -m venv env_tcc_eeg

py -m venv env_tcc_eegv2
```
> Activating env

```cmd
.\env_tcc_eeg\Scripts\activate

.\env_tcc_eegv2\Scripts\activate
```
> Leaving virtual env

```cmd
deactivate
```

> Updating pip

```cmd
py -m pip install --upgrade pip
```

> Installing packages

```cmd
py -m pip install -r requirements.txt

py -m pip install -r requirementsV2.txt
```

https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/

https://pypi.org/project/Braindecode/#history