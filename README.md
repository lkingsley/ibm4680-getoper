## Getoper
This is an IBM 4680 command line application to retrieve operators information.

The application needs to be compiled with the IBM 4680 Basic Compiler and linked with the LINK86 Linkage Editor.

The EAMOPERA.DAT file must be in the same folder as the application. To run the app you just have to pass the operator id as an argument.
e.g:
```
C:ADX_UPGM/GETOPER 1234
```

Result:
```
OPERATOR: 0000001234
PASSWD:   0000001234
OPERNAME: LUIS KINGSLEY
OPTIONS:  01
USEREXIT: SALES FUNCTIONS
```
