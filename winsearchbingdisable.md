# How to disable Win11/Win10 bing search

## **Disclaimer**
This operation requires the user to modify Windows Registers. Do this at your own risk.

## Tutorial
1. Press WIN+R, and type in `regedit`, press enter
2. In RegEdit go to `HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows`
3. Create a new key and name it `Explorer`
4. Add a new DWORD with the name `DisableSearchBoxSuggestions` and give it a value of `1`
5. Reboot your PC and Windows should no longer give you bing search results :-)
