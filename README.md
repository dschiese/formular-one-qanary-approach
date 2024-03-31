### Context
In the 2022 summer semester the module *Softwareprojekt I* (Software Project I) brought forth a project for digital form processing, following an interactive and chatbot-driven approach. 

The result was a working chatbot that could lead users through some - pre-chosen - formulas. However, the approach didn't follow a linked-data approach. The extension of this project with linked-data technologies could solve some problems and provide some new features.

For example, creating a vocabulary for formulas could end up in triples like the following:

```
<FORMULA> ex:relatedFormulas <RELATED_FORMULAS> ;
          ex:needsInformation <NEEDS_INFORMATION> ;
          ex:dependentFormulas <DEPENDENT_FORMULAS> .
```

These triples are just examples, however, it's imaginable that this could increase the chatbot's capability in conversations (with related formulas). Furthermore, the process might be easier to implement and follow (needed information as well as dependent formulas).
