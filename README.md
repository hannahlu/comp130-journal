# comp130-journal
Base repository for COMP130 research journal

## When and Why Your Code Starts to Smell Bad.

Technical Debt: "not quite right code which we postpone making it right." [2]

Bad code smells are surface-level signs, that suggest a deeper problem within code. Such symptoms in code are often attributed to the pressure on professional programmers to develop features in tight time frames, with release dates prioritised over code quality. 

Bad code smells increase the size of technical debt in a project, tending to result from poor design and implementation planning. Tight deadlines for programmers may encourage professionals to devout less time to planning the design, instead diving into creating tangible results.

The evolution of software is often blamed for the existence of bad code smells, however, the study found such problems within code tended to be present from creation. As such, it should be possible to prevent bad code smells with effective quality checks when committing code to a project. Another common believe held, is that newcomers are chiefly responsible for bad code smells, yet, this papers argues developers with high workloads and release pressure proved to be a higher contributor. It is argued that current tools used to manage bad code smells, such as static-code analysis and constraint-based reasoning over metric values, do not target the reason such symptoms originate. [1]

## What Should We Teach New Software Developers? Why?

This paper argues that there is a 'disconnect between computer science education and what industry needs', with industry often complaining graduates lack programming proficiency. 

Stroustrup suggests students tend to struggle with connecting topics covered in different classes, leading to graduates with good grades, yet lacking the ability to produce functioning and maintainable code. 

Computer science education, Stroustrup argues, needs a standardised structure with a clearer definition of what an individual needs in order to earn the title of Computer Scientists. Perhaps one day leading to licensing of Computer Science professionals. In order to do so, professionals should not purely posses a generalised understanding of computer science, but have obtained a specialism within the field.[3]

## Making the Mainstream Accessible: Redefining the Game. 
### Case Study: _AudioQuake_

_Quake_ [4] is one of the first FPS mainstream games to be adapted to suit the visually impaired, in the form of _AudioQuake_,  which uses an auditory interface [5]. The creators were keen to not only enable basic game play, but ensure blind users could participate online and in the building of their own level maps.

Adapting _Quake_ into an accessible game for the visually impaired involved several stages of development, beginning with the low-level requirments necessary to implement an auditory interface. Audio needed to be improved to create more relastic cues for the visually impaired, such as indicating room size through the use of echos. 

_AudioQuake_ is part of the AGRIP project [6] which aims for games, not only playable by the disabled, but that enables them to play evenly matched with or against able-bodied players, create their own map levels and adjust game settings. _AudioQuake_ was built with LDL (Level Description Language), an XML programming language designed specfically to enable developers to describe 3D spaces and for visually impaired players to be able to create 3D levels.

## AccTrace: Accessibility in Phases of Requirements Engineering, Design and Coding Software

Although considerable research and proposals for improving Software Engineering for accessibility exsist, developers rarely understand how to code accessible systems. AccTrace [8] is a Case Tool designed to use an onotology, a method for showing a group of concepts and the relationships between them, to propose and define a technical procedure for implementing accessible gaming. AccTrace was also designed to enable tracebility, enabling developers to acertain the origin of certain elements within a systems design. [8]

### Disability-aware software engineering for improved system accessibility and usability
"
1. Heterogeneous user characteristics: In addition to considering people without disability, the software design method should accommodate to a great extent the variety of known disabilities.
2. Adaptive and personalised interface: The interface provides the platform of interaction between the user and the software. Therefore, the inability to use a particular software product may lie in its interface support. It is imperative that the interface adapts to specific user needs; for instance colours and font sizes for people with visual impairment, it should also be able to provide audio support for blind people, and also appropriate symbols, signs or icons for people with reading problem. Users should also be able to personalise such interface supports.
3. Support for accessibility using assistive components: For certain user groups with special needs, the accessibility of the adaptive and personalised interface may require additional components (hardware, software, or both). For instance text to speech, screen readers, specialised keyboards and mice, etc.
4. Involvement of an expert on disability issues: It is vital to involve an expert on disability issues, especially during feasibility and requirement phases of the software development life-cycle. This ensures that disability requirements are appropriately captured should the project be feasible
5. Involve target user group in the testing phase: This implies engaging people with identified disability in the testing of the software product. This ensures that the right software product is being developed. Generally, people with disabilities should be included in the decision making process and not only during the testing phase." [9]


### Onotology

### Traceability

### Accessibility as Standard in Game Design, Software Engineering in education

### References

[1] M. Tufano; F. Palomba; G. Bavota; R. Oliveto; M. Di Penta; A. De Lucia; D. Poshyvanyk, "When and Why Your Code Starts to Smell Bad (and Whether the Smells Go Away)," in IEEE Transactions on Software Engineering , vol.PP, no.99, pp.1-1

[2] Ward Cunningham. 1992. "The WyCash portfolio management system. In Addendum to the proceedings on Object-oriented programming systems, languages, and applications" (Addendum) (OOPSLA '92), Jerry L. Archibald and Mark C. Wilkes (Eds.). ACM, New York, NY, USA, 29-30.

[3]Stroustrup, B. (2010). _"What should we teach new software developers? Why?"_, Communications of the ACM, 53(1), 40.

[4] id Software 1996, _Quake_, video game, Linux, GT Interactive, New York. 

[5] Atkinson, M.T. et al, 2006. _"Making the mainstream accessible: redefining the game."_ IN: Proceedings, Sandbox Symposium 2006, ACM SIGGRAPH Symposium on Videogames, Boston, Massachusetts, July 30-31, pp. 21-28

[6] Atkinson, M.T. and Gucukoglu, S. (2003 - 2012). “AGRIP Project”. AGRIP Project [Online]. Available: http://agrip.org.uk. [Accessed: March, 12, 2017].

[7]	Atkinson, M.T. and MACHIN, C.H.C., 2009. _"Proof-of-concept 3D level creation tool for blind gamers."_ California State University, Northridge Center on Disabilities' 24th Annual International Technology and Persons with Disabilities Conference (CSUN 2009), 16-21 March, Los Angeles, CA

[8] R. G. De Branco, M. I. Cagnin, and D. M. B. Paiva, “AccTrace: Accessibility in phases of requirements engineering, design, and coding software,” in Proceedings - 14th International Conference on Computational Science and Its Applications, ICCSA 2014, 2014, pp. 225–228.

[9] J. T. Nganji and S. H. Nggada, “Disability-aware software engineering for improved system accessibility and usability,” Int. J. Softw. Eng. its Appl., 2011.
