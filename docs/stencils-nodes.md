
Source :~ <http://compendiumld.open.ac.uk/documentation/version1.0/QuickRefGuides/stencilsAndNodes/>

<!-- <style> object.32p { height: 32px; width: 32px; } object.63p { height: 109px; width: 63px; } </style> -->

## CompendiumLD stencils and node types

This page summarises the nodes and icons that CompendiumLd provides for creating maps or models of learning designs. These nodes and icons are grouped into several stencils according to their purpose.

*   [Core learning design stencil](#ldStencil)  
    The learning design stencil contains nodes for creating models of learning activities.
*   [Sequence mapping stencil](#sequence)  
    The Sequence mapping stencil contains nodes to help the designer layout maps of learning activities in "_swim lanes_". It includes headings for each "_swim-lane_" in a sequence map, and a template containing a pre-arranged layout of these swim-lanes.
*   [Conditional stencil](#conditional)  
    The Conditional stencil is intended to express conditions of the type “_if X then Y else Z_” within a design, as a means of including different learning pathways within the design.
*   [Standard nodes](#standard)  
    a set of nodes used for applications such as issue mapping in meetings and requirements generation and analysis.

### <a name="ldStencil"></a>Core learning design stencil 

The learning design stencil contains 8 nodes for creating models of learning activities. The 8 nodes are shown in the [picture below](#ldIcons), which illustrates how nodes for related purposes share similar visual characteristics. A more detailed description of the intended purpose and functionality of each node given in the [node details table](#ldNodeDetails).

<a name="ldIcons"></a>
<div style="width:670px; height:350px"><object data="./images/cld-icons-new-font-12pt.svg" width="100%" height="100%" type="image/svg+xml">![Image showing CompendiumLD's core learning design icons](images/cld-icons-font-12pt.jpg)</object></div>

CompendiumLD's 8 learning design node icons and their functions

<a name="ldNodeDetails"></a>

Learning design node details: a description of each node's purpose and functionality

**Tip:** when the learning design stencil is open and visible, you can create nodes by holding down the ‘Alt’ key and typing the number shown in the left hand side column in the table below (e.g. Alt-1 to create an ‘Activity’ node).


---

<table class="nodeTable">
<tbody>

<tr>
<td width="2%"></td>
<th scope="col" width="11%">Node name</th>
<th scope="col" width="7%">Icon</th>
<th scope="col" width="77%">Description</th>
</tr>

<tr>
<td width="2%">1</td>
<th scope="row" width="11%">Activity</th>
<th width="7%">
<object data="../../../../icons/vector/activity.svg" class="32p" type="image/svg+xml">![Activity node icon](stencils+node-types_files/image001.gif)</object>
</th>
<td width="78%"><a name="activityNode"></a>

CompendiumLD’s Activity node is for laying out maps of learning activities. Double-clicking an Activity node opens it to reveal the Activity’s contents. The contents can be any combination/layout of any of CompendiumLD’s nodes and links (if the Activity is a newly created node it will be empty until other nodes and links are added). Learning design specific functions provided by Activity node’s include a specific menu available via a mouse right-click on the white space background of an Activity map. Using this menu you can display e.g. timing information for the activity.

The "[Doing more with CompendiumLD](../../../../documentation/version1.0/videos/#doingMore)" slideshow explains how to add timing information.

</td>
</tr>

<tr>
<td width="2%">2</td>
<th scope="row" width="11%">Learner Output</th>
<th width="7%">
<object data="../../../../icons/vector/learner_output_other.svg" class="32p" type="image/svg+xml">![Learner output node icon](stencils+node-types_files/image002.gif)</object>
</th>
<td width="78%"><a name="learnerOutputNode"></a>

The Learner Output node is intended to represent material that a learner creates during a learning activity.

When the user creates a Learner Output node they are prompted to choose the way it will be assessed from: ‘formative’, ‘summative’, or ‘other’. The icon displayed depends on the choice made, i.e.

_summative assessment_: <object data="../../../../icons/vector/learner_output_summative.svg" class="32p" type="image/svg+xml" align="middle">![Summative assessment node icon](stencils+node-types_files/image003.gif) </object> , _formative assessment_: <object data="../../../../icons/vector/learner_output_formative.svg" class="32p" type="image/svg+xml" align="middle"> ![Formative assessment node icon](stencils+node-types_files/image004.gif) </object> , or '_other_’ type of assessment: <object data="../../../../icons/vector/learner_output_other.svg" class="32p" type="image/svg+xml" align="middle"> !['Other' assessment node icon](stencils+node-types_files/image002.gif) </object> .

</td>
</tr>

<tr>
<td width="2%">3</td>
<th scope="row" width="11%">Learning Outcome</th>
<th width="7%">
<object data="../../../../icons/vector/learning_outcome.svg" class="32p" type="image/svg+xml">![Learning outcome node icon](stencils+node-types_files/image005.gif)</object>
</th>
<td width="78%"><a name="learningOutcomeNode"></a>
The Learning Outcome node is intended to represent a learning outcome, and be linked to a leaner’s task or activity.
</td>
</tr>

<tr>
<td width="2%">4</td>
<th scope="row" width="11%">Resource</th>
<th width="7%">
<object data="../../../../icons/vector/resource.svg" class="32p" type="image/svg+xml">![Resource node icon](stencils+node-types_files/image006.gif)</object>
</th>
<td width="78%"><a name="resourceNode"></a>

The Resource node can be used to represent a document, video or any other object that the learner utilises during a learning activity. It is intended to represent resources which do not yet exist, but which the designer plans to implement. If a resource does already exist in some form at the time the activity is being designed (e.g. a draft Word file or Image) it may be dragged and dropped onto the Activity instead of using this Resource node. These existing resources will be represented on the Activity map by a standard icon e.g. ![Word icon](stencils+node-types_files/image007.gif) for Word files or![PDF/Acrobat icon](stencils+node-types_files/image008.gif) for PDF files.

Please see "[Doing more with CompendiumLD](../../../../documentation/version1.0/videos/#doingMore)" to find out how to add and display existing resources such as web pages, documents and presentations. Tip: you can drag and drop documents and other files into CompendiumLD.
</td>
</tr>

<tr>
<td width="2%">5</td>
<th scope="row" width="11%">Role</th>
<th width="7%">
<object data="../../../../icons/vector/role.svg" class="32p" type="image/svg+xml">![Role node icon](stencils+node-types_files/image009.gif)</object>
</th>
<td width="78%"><a name="roleNode"></a>

The Role node is used to represent actors (e.g. students and tutors) who play specific roles in the Activity being designed.

When the users create a Role node they are prompted to choose from: ‘Student’, ‘Tutor’ or ‘Other’. The ‘Other’ role may be used to model practice based support roles for example.

</td>
</tr>

<tr>
<td width="2%">6</td>
<th scope="row" width="11%">Stop</th>
<th width="7%">
<object data="../../../../icons/vector/stop.svg" class="32p" type="image/svg+xml">![Stop node icon](stencils+node-types_files/image010.gif)</object>
</th>
<td width="78%"><a name="stopNode"></a>
The Stop node is used to represent the point the activity finishes for a particular role player. For students, all the learning outcomes linked to the activity should have been addressed by the time the student reaches this node.
</td>
</tr>

<tr>
<td width="2%">7</td>
<th scope="row" width="11%">Task</th>
<th width="7%">
<object data="../../../../icons/vector/task.svg" class="32p" type="image/svg+xml">![Task node icon](stencils+node-types_files/image011.gif)</object>
</th>
<td width="78%"><a name="taskNode"></a>

The Task node is used to represent an action performed by an actor (usually either a student or a tutor). You can add the expected time to complete the task by right-clicking on a task node (the task times will be displayed if ''Show task times' is enabled).

Please see "[Doing more with CompendiumLD](../../../../documentation/version1.0/videos/#doingMore)" to find out how to add and display timing information.

</td>
</tr>

<tr>
<td width="2%">8</td>
<th scope="row" width="11%">Tool</th>
<th width="7%">
<object data="../../../../icons/vector/tool.svg" class="32p" type="image/svg+xml">![Tool node icon](stencils+node-types_files/image012.gif)</object>
</th>
<td width="78%"><a name="toolNode"></a>

The Tool node is used to represent a tool in a learning activity. Tools are utilities which actors use to create outputs or to interact. When the user creates a Tool node the are prompted to choose one of ‘Blog’, ‘E-portfolio’, ‘Forum’, ‘Instant messaging’, ‘Podcast’, ‘Simulation’, ‘Virtual World’, ‘Wiki’ or ‘Other’. Typically a tool node will be used to link a Task performed by one actor (e.g. a student) with another Task performed by a different actor (another student or a tutor), and/or with an Output node.

There is also a help option on the menu presented to enable the user to a select the tool type. Selecting this opens a web search of selected sites known to contain information about tools and learning design, see e.g. this [example search for ‘wiki’][search].

</td>
</tr>

</tbody>
</table>

**Tip:** when the learning design stencil is open and visible, you can create nodes by holding down the ‘Alt’ key and typing the number shown in the left hand side column in the table (e.g. Alt-1 to create an ‘Activity’ node).


---
### <a name="sequence"></a>Sequence mapping or swim-lane stencil


The Sequence mapping or swim-lane stencil contains nodes to help the designer layout maps of learning activities.

<table class="nodeTable">
<tbody>

<tr>
<td width="2%"></td>
<th scope="col" width="13%">Node name</th>
<th scope="col" width="7%">Icon</th>
<th scope="col" width="74%">Description</th>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Sequence map</th>
<th width="7%">
<object data="../../../../icons/vector/activity.svg" class="32p" type="image/svg+xml">![Activity node icon](stencils+node-types_files/image001.gif)</object>
</th>
<td width="80%">
This is an activity map with the nodes below already laid out to get you started quickly.
</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Date/Time schedule marker</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/clock.svg" width="50" height="50" type="image/svg+xml">![Clock icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Clock.png)</object>
</th>
<td width="80%">
This is used to indicate a particular time and/or date during a learning activity e.g. ‘week 3’ or ‘2<sup>nd</sup> hour’.
</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Intent and challenges</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/intent_and_challenges.svg" class="63p" type="image/svg+xml">![Intent icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Intent.gif)</object>
</th>
<td width="80%">

A design should look to capture or express what the designer is aiming to achieve pedagogically when creating a design and what they consider to be the important challenges to learning presented by objects or associations between objects elsewhere in the design. (For example, the common challenges experienced around teaching magnetism, or the common problems of wikis). During design, populating this column should help the designer better understand the key pedagogic design problems; after design it may help them determine the closeness of fit between their initial intent and actual solution.

</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Learning output</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/output.svg" class="63p" type="image/svg+xml">![Learning output icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Output.gif)</object>
</th>
<td width="80%">

The output may be anything from a written assignment to a subtle observation of behaviour. The outputs of learning, may be for student’s future use, for summative or formative assessment, for research, for evaluation (can better use be made of outputs by students or teachers), for workload planning, or for quality/teaching assurance purposes. It is only from the outputs of learning activity that a teacher will know if learning outcomes (an aspect of what is to be learnt) have been met.

</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">What is to be learnt</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/learnt.svg" class="63p" type="image/svg+xml">![What is to be learnt? node icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Learnt.gif)</object>
</th>
<td width="80%">

A design should clearly show what the designer is anticipating the student will learn. There is widespread consensus that learning outcomes, or objectives, are central to any design. Although there are varying ways of classifying learning outcomes, they will commonly include knowledge and understanding, skills and attitudes and may be expressed as specific objectives appropriate to individual activities and/or broader outcomes of the unit of learning.

</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Student activity</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/student_activity.svg" class="63p" type="image/svg+xml">![Student activity node icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_SActivity.gif)</object>
</th>
<td width="80%">
A description of what the student is asked to do during the learning activity, or of what is thought that they actually will do.
</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Media and tools</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/media+tools.svg" class="63p" type="image/svg+xml">![Media and tools node icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Tools.gif)</object>
</th>
<td width="80%">
The tools and media used to deliver resources to the students. See ‘Student resources’ below.
</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Student resources</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/resources.svg" class="63p" type="image/svg+xml">![Student resources node icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Resources.gif)</object>
</th>

<td width="80%">

A description of the semantics and meaning of material to be delivered to students. It is to be delivered via the media and tools . Examples include a description of a theory, which could be delivered in a printed document, in a web page, via a simulation, or in a combination of these three media and tools.

</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="13%">Support roles</th>
<th width="7%">
<object data="../../../../icons/vector/sequence-mapping/support_roles.svg" class="63p" type="image/svg+xml">![Support roles node icon](../../../../icons/raster/sequence-mapping/nodeimages/SMT_Support.gif)</object>
</th>
<td width="80%">
Support will likely include the teacher but can also include others involved in the learning such as work based mentors, student support services or, indeed, other learners.
</td>
</tr>

</tbody>
</table>


---
### <a name="conditional"></a>Conditional stencil


The Conditional stencil is intended to express conditions of the type “if X then Y else Z” within a design, as a means of including different learning pathways within the design.

<table class="nodeTable">
<tbody>

<tr>
<td width="2%"></td>
<th scope="col" width="11%">Node name</th>
<th scope="col" width="7%">Icon</th>
<th scope="col" width="78%">Description</th>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="11%">Condition</th>
<th width="7%">
<object data="../../../../icons/vector/conditional/condition.svg" class="32p" type="image/svg+xml">![Condition node icon](../../../../icons/raster/conditional/nodeimages/id_condition.png)</object>
</th>
<td width="78%">

The Condition node is used to express a condition that affects a student’s path through a learning activity. It can be used to show conditions that must be true or false, typically expressed as a question e.g. “Student passes formative test?” or “Student prompted to redraft essay?”  
Compendium’s Question or Issue node ( <object data="../../../../icons/vector/standard/issue.svg" width="16" height="16" type="image/svg+xml">![Issue node icon](../../../../icons/raster/standard/nodeimages/issue.png) </object> ) has not been used to express a condition because a CompendiumLD condition needs a precise answer, either true or false, whereas a Compendium Question can have many alternative answers. The design of the Condition node has been made similar to that of the Question node to reflect that a Condition may be regarded as a special case of a Question.

</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="11%">True</th>
<th width="7%">
<object data="../../../../icons/vector/conditional/true.svg" class="32p" type="image/svg+xml">![True node icon](../../../../icons/raster/conditional/nodeimages/id_true.png)</object>
</th>
<td width="78%">
The true node is used to show the path that is followed if the condition is true.
</td>
</tr>

<tr>
<td width="2%"></td>
<th scope="row" width="11%">False</th>
<th width="7%">
<object data="../../../../icons/vector/conditional/false.svg" class="32p" type="image/svg+xml">![False node icon](../../../../icons/raster/conditional/nodeimages/id_false.png)</object>
</th>
<td width="78%">
The false node is used to show the path that is followed if the condition is true.
</td>
</tr>

</tbody>
</table>


---

### <a name="standard"></a>Standard nodes


[Compendium](http://compendium.open.ac.uk/institute/) (the tool upon which CompendioumLD is based) includes a set of nodes used for applications such as issue mapping in meetings; requirements generation and analysis; meeting management (agendas, minutes); action item and issue tracking; requirements management; classification; management templates; testing and reference databases. These can also be used in CompendiumLD e.g. for adding notes or raising questions about design decisions.


<table class="nodeTable">
<tbody>

<tr>
<td width="3%"></td>
<th scope="col" width="13%">Node name</th>
<th scope="col" width="7%">Icon</th>
<th scope="col" width="75%">Description</th>
</tr>

<tr>
<td width="3%">
?
</td>
<th scope="row" width="13%">Question</th>
<th width="7%">
<object data="../../../../icons/vector/standard/issue.svg" class="32p" type="image/svg+xml">![Issue node icon](../../../../icons/raster/standard/nodeimages/issue.png)</object>
</th>
<td width="75%">
Ask a question or raise an issue.
</td>
</tr>

<tr>
<td width="3%">
a
</td>
<th scope="row" width="13%">Answer</th>
<th width="7%">
<object data="../../../../icons/vector/standard/poistion.svg" class="32p" type="image/svg+xml">![Answer node icon](../../../../icons/raster/standard/nodeimages/position.png)</object>
</th>
<td width="75%">
Provide a possible answer to a question.
</td>
</tr>

<tr>
<td width="3%">
m
</td>
<th scope="row" width="13%">Map</th>
<th width="7%">
<object data="../../../../icons/vector/standard/map.svg" class="32p" type="image/svg+xml">![Map node icon](../../../../icons/raster/standard/nodeimages/map.png)</object>
</th>
<td width="75%">
(a) Create a “picture” of the relationships between ideas (b) Group questions and ideas together in meaningful clusters (c) Create associative links between nodes.
</td>
</tr>

<tr>
<td width="3%">
l
</td>
<th scope="row" width="13%">List</th>
<th width="7%">
<object data="../../../../icons/vector/standard/list.svg" class="32p" type="image/svg+xml">![List node icon](../../../../icons/raster/standard/nodeimages/list.png)</object>
</th>
<td width="75%">

(a) Create a sortable list of nodes (b) Hold the results of a search (e.g. create a
catalogue of items) (c) Create a collection of nodes that don’t need to be linked with each other (via associative links).

</td>
</tr>

<tr>
<td width="3%">
+
</td>
<th scope="row" width="13%">Pro</th>
<th width="7%">
<object data="../../../../icons/vector/standard/pro.svg" class="32p" type="image/svg+xml">![Pro node icon](../../../../icons/raster/standard/nodeimages/plus.png)</object>
</th>
<td width="75%">
Support an idea.
</td>
</tr>

<tr>
<td width="3%">
-
</td>
<th scope="row" width="13%">Con</th>
<th width="7%">
<object data="../../../../icons/vector/standard/minus.svg" class="32p" type="image/svg+xml">![Con node icon](../../../../icons/raster/standard/nodeimages/minus.png)</object>
</th>
<td width="75%">
Argue against an idea.
</td>
</tr>

<tr>
<td width="3%">
r
</td>
<th scope="row" width="13%">Reference</th>
<th width="7%">
<object data="../../../../icons/vector/standard/reference.svg" class="32p" type="image/svg+xml">![Reference node icon](../../../../icons/raster/standard/nodeimages/reference.png)</object>
</th>
<td width="75%">
Bring in a link to an external file (such as a spreadsheet, picture or document) or drag and drop the file directly onto the map.
</td>
</tr>

<tr>
<td width="3%">
n
</td>
<th scope="row" width="13%">Note</th>
<th width="7%">
<object data="../../../../icons/vector/standard/note.svg" class="32p" type="image/svg+xml">![Note node icon](../../../../icons/raster/standard/nodeimages/note.png)</object>
</th>
<td width="75%">
Provide extra information about another node or the current view
</td>
</tr>

<tr>
<td width="3%">
d
</td>
<th scope="row" width="13%">Decision</th>
<th width="7%">
<object data="../../../../icons/vector/standard/decision.svg" class="32p" type="image/svg+xml">![Decision node icon](../../../../icons/raster/standard/nodeimages/decision.png)</object>
</th>
<td width="75%">
Resolve a question ± link it to an idea, or right-click on idea to change directly to a decision node.
</td>
</tr>

<tr>
<td width="3%">
u
</td>
<th scope="row" width="13%">Argument</th>
<th width="7%">
<object data="../../../../icons/vector/standard/argument.svg" class="32p" type="image/svg+xml">![Argument node icon](../../../../icons/raster/standard/nodeimages/argument.png)</object>
</th>
<td width="75%">
Present a general argument, usually in response to an answer or position.
</td>
</tr>

</tbody>
</table>


**Tip:** you can create these nodes by typing the shortcut keys in the left hand side column.

[archive]: https://web.archive.org/web/20170618125234/http://compendiumld.open.ac.uk/documentation/version1.0/QuickRefGuides/stencilsAndNodes/
[search]: https://google.com/cse?cx=000971387191123125524%3Alworuyth0qs&ie=UTF-8&q=wiki&sa=Search&siteurl=www.google.com%2Fcse%2Fhome%3Fcx%3D000971387191123125524%253Alworuyth0qs
  "Example search for ‘wiki’"

---
