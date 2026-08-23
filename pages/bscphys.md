--- 
layout: page
title: BSc Physics  
bootstrap: true
permalink: /bscphys/
subtitle: "Under Utkal University" 
feature-img: "assets/img/pexels/computer.jpeg"
tags: [Page, phy, utkal]
---
* This will become a table of contents (this text will be scrapped).
{:toc}

# Physics @ Utkal University Colleges 

Model Curriculum for Three/Four Year Degree Course (With Multiple Entry /Exit Option) Based 
on NEP-2020 for Physics by Odisha State Higher Education Council, Bhubaneswar, 
Government of Odisha provides the following subjects:

##### Semester I
* Core I -  Mathematical Physics-I
* Core II-  Mechanics
  
##### Semester II
* Core III-  Electricity and Magnetism
* Core IV -  Mathematical Physics-II

##### Semester III
* Core V-   Waves and Optics
* Core VI-  Mathematical Physics-III
* Core VII-  Thermal Physics

##### Semester IV
* Core VIII-  Analog Systems
* Core IX-  Basic Instrumentation
* Core X-  Nuclear and Particle Physics

##### Semester V
* Core XI-   Digital Systems
* Core XII-  Quantum Mechanics and Applications
* Core XIII-  Solid State Physics

##### Semester VI
* Core XIV-  Electromagnetic Theory
* Core XV-  Statistical Mechanics

##### Semester VII (4th year)
* Core XVI-  Mathematical Methods in Physics
* Core XVII-  Classical Mechanics
* Core XVIII-  QUANTUM MECHANICS
* Core XIX-  LABORATORY: COMPUTATIONAL PHYSICS

##### Semester VIII (4th year)
* Core XX-  Classical Electrodynamics
* Core XXI-  QUANTUM MECHANICS-II
* Core XXII-  Electronics
* Core XXIII-  Laboratory: Optics and Modern Physics Lab
      


{% assign groupnames = site.bscphys | group_by: 'group' %}
{% for group in groupnames %}

{% comment %}
---
<div class="dropdown">
  <button class="dropbtn">{{ group.name | capitalize }}</button>
  <div class="dropdown-content">
    {% for class in group.items %}
    <a href="{{ class.url | relative_url }}">{{ class.title }}</a>
    {% endfor %}
  </div>
</div>

{% endcomment %}
---
<details><summary><h3><svg width="400" height="60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gradient1">
      <stop offset="0%" stop-color="#ffffff" />
      <stop offset="100%" stop-color="#000000" />
    </linearGradient>
    <mask id="mask4">
      <rect x="0" y="0" width="250" height="60" fill="url(#gradient1)" />
    </mask>
  </defs>
  <rect x="0" y="0" width="250" height="60" fill="red" mask=" url(#mask4)"/>
  <text fill="#ffffff" font-size="30" font-family="Optima" x="10" y="30">{{ group.name | capitalize }}</text>
</svg></h3></summary>

<ol class="fa-ul">
{% for class in group.items %}
<li><span class="fa-li"><i class="fa-solid fa-book"></i></span>
<a href="{{ class.url | relative_url }}">{{ class.title }}</a> 
  {% if class.subtitle %} - {{ class.subtitle }} {% endif %} 
</li>
{% endfor %}
</ol>
</details>


{% endfor %}

--------

# CBCS Model syllabus 2019
Prior to the adoption of the National Education Policy (NEP) 2020, Utkal University implemented the Model Syllabus 2019 as prescribed by DHE, Odisha. This system served as the standardized educational framework for undergraduate programs across the state prior to the current reforms. The DHE, Odisha, had developed the 2019 syllabus to standardize undergraduate education across the state's universities and colleges. This system typically operated under a **CBCS (Choice Based Credit System)** framework and a semester-based structure, which was the prevailing system nationwide before the holistic restructuring mandated by NEP 2020.

The structure of the three-year B.Sc. Physics Honours program at Utkal University, under the 2019 DHE, Odisha CBCS model syllabus, was divided into six semesters with specific course types: Core Courses (CC), Ability Enhancement Compulsory Courses (AECC), Skill Enhancement Courses (SEC), and Discipline Specific Elective (DSE) courses. 

### The structure of the curriculum was as follows:
<table>
  <thead>
    <tr>
      <th>Course Type<br>
        Credits (Theory + Practical + Tutorial)</th>
      <th>Course Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2"><strong>Semester 1</strong>
      Tot. Cr. :24, Marks: 400</td>
    </tr>
    <tr>
      <td><strong>AECC-I</strong>(2+0+0)</td>
      <td>English/ MIL Communication/ Environmental Science</td>
    </tr>
    <tr>
      <td><strong>Core-I</strong> (4+2+0)</td>
      <td>Mathematical Physics-I<br/> (Calculus &amp; Vectors)</td>
    </tr>
    <tr>
      <td><strong>Core-II</strong> (4+2+0)</td>
      <td>Mechanics</td>
    </tr>
    <tr>
      <td><strong>GE-I</strong> (4+2+0) or (5+0+1)</td>
      <td>GE-1.1 (Chemistry/ Mathematics)</td>
    </tr>
    <tr>
      <td colspan="2"><strong>Semester II</strong>
      Tot. Cr. :24, Marks: 400</td>
    </tr>
    <tr>
      <td><strong>AECC-II</strong> (2+0+0)</td>
      <td>Environmental Science/ English/ MIL Communication</td>
    </tr>
    <tr>
      <td><strong>Core-III</strong> (4+2+0)</td>
      <td>Electricity and Magnetism</td>
    </tr>
    <tr>
      <td><strong>Core-IV</strong> (4+2+0)</td>
      <td>Waves and Optics</td>
    </tr>
    <tr>
      <td><strong>GE-II</strong> (4+2+0) or (5+0+1)</td>
      <td>GE-2.1 (Mathematics/ Chemistry)</td>
    </tr>
    <tr>
      <td colspan="2"><strong>Semester III</strong>
      Tot. Cr. :28, Marks: 500</td>
    </tr>
    <tr>
      <td><strong>Core-V</strong> (4+2+0)</td>
      <td>Mathematical Physics-II</br> (Fourier series,  Polynomials & PDE)</td>
    </tr>
    <tr>
      <td><strong>Core-VI</strong> (4+2+0)</td>
      <td>Thermal Physics</td>
    </tr>
    <tr>
      <td><strong>Core-VII</strong> (4+2+0)</td>
      <td>Analog Systems and Applications</td>
    </tr>
    <tr>
      <td><strong>SEC-I</strong> (2+0+0)</td>
      <td>Skill Enhancement Course-I (from Physics)</td>
    </tr>
    <tr>
      <td><strong>GE-III</strong> (4+2+0) or (5+0+1)</td>
      <td>GE-1.2 (Chemistry/ Mathematics)</td>
    </tr>
    <tr>
      <td colspan="2"><strong>Semester IV</strong>
      Tot. Cr. :28, Marks: 500</td>
    </tr>
    <tr>
      <td><strong>Core-VIII</strong> (4+2+0)</td>
      <td>Mathematical Physics-III</br>(Complex Analysis & Integral transforms)</td>
    </tr>
    <tr>
      <td><strong>Core-IX</strong> (4+2+0)</td>
      <td>Elements of Modern Physics</td>
    </tr>
    <tr>
      <td><strong>Core-X</strong> (4+2+0)</td>
      <td>Digital Systems and Applications</td>
    </tr>
    <tr>
      <td><strong>SEC-II</strong> (2+0+0)</td>
      <td>Skill Enhancement Course-II (from Physics)</td>
    </tr>
    <tr>
      <td><strong>GE-IV</strong> (4+2+0) or (5+0+1)</td>
      <td>GE-2.2 (Mathematics/ Chemistry)</td>
    </tr>
    <tr>
      <td colspan="2"><strong>Semester V</strong>
      Tot. Cr. :24, Marks: 400</td>
    </tr>
    <tr>
      <td><strong>Core-XI</strong> (4+2+0)</td>
      <td>Quantum Mechanics and Applications</td>
    </tr>
    <tr>
      <td><strong>Core-XII</strong> (4+2+0)</td>
      <td>Solid State Physics</td>
    </tr>
    <tr>
      <td><strong>DSE-I</strong> (5+0+1)</td>
      <td>Classical Dynamics </td>
    </tr>
    <tr>
      <td><strong>DSE-II</strong> (5+0+1)</td>
      <td>Nuclearand and Particle Physics</td>
    </tr>
    <tr>
      <td colspan="2">
      <strong>Semester VI</strong>
      Tot. Cr. :24, Marks: 400</td>
    </tr>
    <tr>
      <td><strong>Core-XIII</strong> (4+2+0)</td>
      <td>Electromagnetic Theory</td>
    </tr>
    <tr>
      <td><strong>Core-XIV</strong> (4+2+0)</td>
      <td>Statistical Mechanics</td>
    </tr>
    <tr>
      <td><strong>DSE-III</strong> (5+0+1)</td>
      <td>Nano Materials and Applications</td>
    </tr>
    <tr>
      <td><strong>DSE-IV</strong> (6) or (4+2+0)</td>
      <td>Project OR Basic Instrumentation </td>
    </tr>
  </tbody>
</table>

* Total Core Papers =14, DSE = 4, Credit =148, Marks = 2600.
* Credits for Core Courses, Generic Electives & DSE 4:: Theory + Practical:: 4+2.
* Credits for Discipline Specific Electives (DSE) 1,2 & 3::Theory + Tutorial:: 5+1 (i.e., no practical).
* Credits for Ability Enhancement Cumpolsory Courses (AECC), Skill Enhancement Cumpolsory Course (SECC) :: Credit 4.
* For Credit 6, Total marks 100:

| Course type | mid | end | Practical | Teaching hours |
|-------------|-----|-----|-----------|----------------|
|Without Practical | 20 | 80 |-- | 50 Theory +10 Tutorial |
|With Practical| 15|60|25|40 Theory +20 Tutorial|


# NEP 2020
The implementation of NEP 2020 introduced a significant paradigm shift in Education sector, most notably through the establishment of the **Four-Year Undergraduate Programme (FYUP)**. Key features of the new system include **flexible multiple entry and exit points**, an updated credit architecture, and a strong emphasis on interdisciplinary studies and vocational skills, moving away from the previous prescriptive model.

Utkal University offers for its affiliated Colleges, **Single Major (Honours) Two Minor Scheme** in lieu of the earler existing **Honours** curriculum. Effective from the **2024–25** academic session, Utkal University has implemented the <b>National Education Policy (NEP) 2020</b> for all undergraduate degree courses. Under the new structure, every paper culminates in a final examination worth a total of **100 marks**. This final exam weightage is 50% for subjects with a practical component and 60% for purely non-practical (theory) subjects, to the gradesheet. Previously known  <b>Honours Core Papers</b> are now officially referred to as <b>Major Papers</b>. Despite changes in examination question patterns and paper redistribution, the core syllabus content of relevant subjects remains consistent with the corresponding new major papers. 

Utkal University has adopted  Single Major (Honours) Two Minor Scheme for its affiliated colleges in place of the Honours stream. The **Physics Single Major two Minors (Chemistry & Math)** will have the following Paper structure as per the regulations of OSHEC.

 <table>
  <thead>
    <tr>
      <th>Semester: </th> <th>I</th> <th>II</th>
      <th>III</th> <th>IV</th> <th>V</th> <th>VI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Major-1-Paper- </td>
      <td>1 & 2 </td>
      <td>3 & 4 </td>
      <td>5, 6 & 7 </td>
      <td>8, 9 & 10 </td>
      <td>11, 12 & 13 </td>
      <td>14 & 15 </td>
    </tr>
     <tr>
      <td>Minor-1-Paper-</td>
      <td>1</td>
      <td>-- </td>
      <td>2</td>
      <td>-- </td>
      <td>3</td>
      <td>-- </td>
    </tr>
      <tr>
      <td>Minor-2-Paper-</td>
      <td>-- </td>
      <td>1</td>
      <td>-- </td>
      <td>2</td>
      <td>-- </td>
      <td>3</td>
    </tr>
     <tr>
      <td>Multi Disciplinary</td>
      <td>MDC 1</td>
      <td>MDC 2</td>
      <td>MDC 3</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
    </tr> 
      <tr>
      <td>AEC</td>
      <td>1 Odia</td>
      <td>2 English </td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
    </tr>
     <tr>
      <td>SEC</td>
      <td>--</td>
      <td>1</td>
      <td>--</td>
      <td>--</td>
      <td>2</td>
      <td>3</td>
    </tr>     
    <tr>
      <td>VAC</td>
      <td>1 ES&DM</td>
      <td>--</td>
      <td>2</td>
      <td>--</td>
      <td>3</td>
      <td>4</td>
    </tr>     
    <tr>
      <td>CES</td>
      <td>-- </td>
      <td>-- </td>
      <td>-- </td>
      <td>Paper 1</td>
      <td>-- </td>
      <td>-- </td>
    </tr>
  </tbody>
</table>

Community Engagement & Service(CES)/ Fieldwork/ Internship.<br>
Papers with 4 credits each: Major(15×4), Minor(6×4), AEC(2×4) & CES(1×4) = 96.<br>
Papers with 3 credits each: MDC(3×3), SEC(3×3) & VAC(4×3) = 30.

### Distribution of Marks
**Every paper has full marks 100 irrespective of credit in a course/ Paper**. In the structured grading system all papers are initially worth a nominal 100 marks, but the components are weighted differently when contributing to the final grade. **The Semester end Theory examination shall be for 100 marks of three hours duration**. However, the weightage shall be 50 or 60 for papers with or without Practical component, respectively. The weightage breakdown provided is as follows:

| Course Type | Without Practical | With Practical |
|-------------|-------------------|----------------|
| Semester end Theory(100) | 60(weighted)| 50(weighted)|
| Continuous evaluation or sessional marks | 20 | 10 |
| Mid Semester Theory mark | 20 | 10 |
| Semester end Practical marks | -- | 20 |
| Mid Semester Practical marks | -- | 10 |

 

#### Distribution of Continuous Evaluation or Sessional Marks: 10/20

<table>
  <thead>
    <tr>
      <th>Course type</th>
      <th>Attendance(5)</th>
      <th>Surprise Test/ Quiz</th>
      <th>Assignment / Presentation</th>
    </tr>  </thead>
  <tbody>
    <tr>
      <td>Without Practical</td>
      <td rowspan="2">Above 95% 5 
      <br>85% -- 94%  4  
      <br>75% -- 84%  3 
      </td>
      <td>10</td>
      <td>05</td>
</tr>
    <tr>
      <td>With Practical</td>
      <td>05</td>
      <td>nil</td>
</tr>
  </tbody>
</table>
