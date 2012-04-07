## Browser support

### Purpose of this document

This document is designed to provide a template for agreeing development deliverables with the client. It is structured to be a modular document where sections can be updated or removed depending on the requirements of the project. [[1](#note-1)]

### Development approach

Our development approach is based on internationally recognised standards and best practice to create accessible, modular, scalable and performant code. By basing our approach on international standards we aim to develop an inclusive experience for all web users; where access to functionality and content is of primary importance and design is used to enhance that experience.

### Understanding support

Access to the Web is as diverse as it's users and in providing support we aim to make Web functionality and content as accessible as possible. Providing support is not about forcing the same visual and behavioural experience across different browsers, where different browsers may have varying capabilities and users may have different requirements. To force a specific experience will prevent users accessing functionality and content.

To identify the level of support we can provide a browser, we grade browsers by the experience they are capable of providing the user.

Where requested we can also [analyse client data](#client-data) and identify specific [client requirements](#client-requirements) to modify the standard [graded browser matrix](#graded-browser-matrix).

#### Analysis of client data

Analysing client user data, through analytics software, we can create an interactive experience suited to specific user requirements. e.g. if the user base primarily uses modern browsers the designed experience can target advanced browser features.

A cut off point for support is recommended at &lt; 2%. [[2](#note-2)]

#### Client requirements

We understand that the client may have specific requirements for interactive development. e.g. support of a specific browser that may otherwise be unsupported or the use of a particular technology that have implications for the development process. [[3](#note-3)]

### Graded browser support

#### Grade A support

Pages rendered in browsers with Grade A support will meet the functional specification, user interface specification and creative design. If a level one browser is incapable of meeting any of these criteria either the particular criteria will need to be altered to match the browser capability or the browser should be reduced to Grade B support.

#### Grade B support

Pages rendered in browsers with Grade B support will meet the functional specification. The majority of the user interface specification and creative design will be met dependent on the capability of the browser, if either criteria is a barrier to meeting the functional specification, the functional specification will take priority.

#### Grade C support

Pages rendered in browsers with Grade C support will meet the functional specification. The user interface specification and creative design will be used as guidance, meeting the functional specification and making content available takes priority.

#### Unsupported

Unsupported browsers will not be reviewed during development or quality assurance.

### Graded browser matrix

The graded browser matrix details browsers, operating systems and their support level during the development process.

| Browser             |  Windows XP      |  Windows 7      | OS 10.7         | iOS 5.x         | Android 2.x     |
|-------------------- | ---------------- | --------------- | --------------- | --------------- | ----------------| 
| Firefox 11.x        |  Grade A support | Grade A support | Grade A support |                 |                 |
| Chrome 18.x         |  Grade A support | Grade A support | Grade A support |                 |                 |
| Safari 5.x          |                  |                 | Grade A support |                 |                 |
| Internet Explorer 9 |                  | Grade A support |                 |                 |                 |
| Internet Explorer 8 | Grade A support  | Grade B support |                 |                 |                 |
| Internet Explorer 7 | Grade B support  |                 |                 |                 |                 |
| iOS Safari          |                  |                 |                 | Grade B support |                 |
| Android webkit      |                  |                 |                 |                 | Grade B support | 


Although browser implementation variations are negligible between operating system, they are included as guidance for [quality assurance](#quality-assurance). [[3](#note-3)]

### Feature definitions

#### Operating system

Testing of particular operating systems will be against the latest non-beta minor version. [[4](#note-4)]

#### Operating system rendered elements

HTML form elements are commonly rendered by the operating system rather than the browser for security reasons. As they are rendered by the operating system, CSS does not have full control of the element's styling. HTML elements rendered by the operating system are expected to deviate from the design due to this limitation.

CSS styling is the preferred method to allow the HTML element to benefit for operating system integration. If HTML elements rendered by the operating system are required to exactly match the design a JavaScript replacement of the element may be developed. [[5](#note-5)]

### Notes

1. This section is for information only and should be removed. <a name="note-1" />  
2. Specific requirements should be agreed to and documented before development begins. <a name="note-2" />  
3. Browsers and operating systems not outlined in the matrix may be included by agreement with the client. <a name="note-3" />  
4. If a particular operating system or version is required it should be agreed to and documented before development begins. <a name="note-3" />  






