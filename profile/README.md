![logo.png](../images/logo.png)

StudyAlign is an open-source software system for setting up online user studies to evaluate web prototypes, such as interactive prototypes with AI features. It simplifies implementing experiment procedures, integration of questionnaires, and data logging. It has a focus on studies in the field of Human-Computer Interaction and human-AI interaction studies
since these studies have been prototyped with web technologies lately.

StudyAlign streamlines HCI online studies and has enabled several studies.

You can find detailed information about the system in our paper `StudyAlign: A Software System for Conducting Web-Based
User Studies with Functional Interactive Prototypes` arXiv: https://arxiv.org/abs/2505.13046 | ACM DL (coming soon): https://doi.org/10.1145/3733053

## Key Features

StudyAlign offers the following key features:

- **UI for creating web-based studies** The Control Panel supports setting up and managing web-based studies and allows for various study designs. Researchers can edit procedures interactively with a setup wizard and select specific parts easily for counter-balancing.
- **Library for integrating prototypes** The Library can be included in existing prototypes and enables the integration into StudyAlign, e.g. to the logging of browser events
- **A frontend for participants** The Study Frontend guides the participants through studies end to end and controls the user flow so participants can only proceed one step at a time.
- **Interaction logging** The system persists log data in the Backend. It supports logging native browser events, like mouse, keyboard, and touch events. Furthermore, it allows the storage of custom data objects.
  Methods for data logging are provided in the Library and can be integrated by researchers as "one-liners", to enable easy data logging from inside prototypes.
- **Sharing of studies** StudyAlign allows the import and export of studies. That way, study schemes can be shared easily as material for papers to support future research.
- **Keeping track of studies** In the long run, research teams can view a history of existing studies and reuse and evolve their designs.


## StudyAlign builds on four software parts.

1. a [backend server](https://github.com/StudyAlign/StudyAlign-backend) for persisting log data, and offering the system's API
2. a [study frontend](https://github.com/StudyAlign/study-frontend) for participants
3. a [control panel](https://github.com/StudyAlign/admin-control-panel) to manage studies
4. a [library](https://github.com/StudyAlign/StudyAlign-library) to integrate prototypes

:books: [The full documentation can be found here!](https://github.com/StudyAlign/docs)


## Philosophy

StudyAlign is part of our vision to advance the methodological aspects of web-based HCI research.

The initial motivation to start the project comes from our experience: we re-implemented experiment logic and logging infrastructure several times across various projects. When we compared our experience to related work, we found similarities: researchers applied the same methods but gave little or no insight into how they implemented them. These researchers supposedly also spend time on the development of software and integration of online services surrounding their research.

We identified this as a challenge to provide a foundation for implementing methods in web-based studies.

StudyAlign allows researchers to focus on designing, developing, and studying interactions since the research methods implemented in our system can be reused across studies. Moreover, we support the vision of allowing researchers to share their study design and enable replication.

## Citation

You can cite StudyAlign as follows:
```
Lehmann, Florian and Buschek, Daniel (2025). StudyAlign: A Software System for Conducting Web-Based User Studies with Functional Interactive Prototypes.
https://arxiv.org/abs/2505.13046
```

arXiv bibtex reference:
```
@misc{lehmann2025studyalign,
    title={StudyAlign: A Software System for Conducting Web-Based User Studies with Functional Interactive Prototypes},
    author={Florian Lehmann and Daniel Buschek},
    year={2025},
    eprint={2505.13046},
    archivePrefix={arXiv},
    primaryClass={cs.HC}
}
```

