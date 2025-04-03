---
layout: page
title: ""
---

<!---
<link rel="shortcut icon" type="image/x-icon" href="./pic/favicon.ico?">
--->


<img style="float: right; 
      margin-top: 0%;
      margin-right: 5%;
      margin-bottom: 0%;
      margin-left: 0%;" 
      src="/pic/Xiang_JMM_2025.jpg" alt = "Xiang Wan Profile" width = "25%">

**_Office:_**
BVM Hall 516, Lake Shore Campus

**_Email:_**
xwan1 [AT] luc [DOT] edu 

**_Tel:_**	
773-508-3554 

**_Office Hours, Spring 2025:_**
- Wednesday 3-5PM
- Wednesday 9-10PM (Zoom; link on Sakai)

**_Departmental Webpage:_**
[<u>https://www.luc.edu/math/profiles/wanxiang.shtml/</u>](https://www.luc.edu/math/profiles/wanxiang.shtml)

**_Mailing Address:_**
6317 N Broadway St, BVM Hall 516, Chicago, IL 60660

***

I'm an applied mathematician with research interests in Partial Differential Equations, Control Theory, and Numerical Analysis. 

Since Fall 2022, I am an assistant professor at the [Department of Mathematics and Statistics](https://www.luc.edu/math/index.shtml), [Loyola University Chicago](https://www.luc.edu/). 
Previously, I was a Visiting Assistant Professor at [Haverford College](https://www.haverford.edu/mathematics-and-statistics), at [the George Washington University](https://math.columbian.gwu.edu/), and a Research Assistant Professor at [Wayne State University](https://clas.wayne.edu/math).

I received my Ph.D in Mathematics in 2017 from [the University of Virginia](https://math.virginia.edu/), under the supervision of [Dr. Irena Lasiecka](https://math.virginia.edu/people/il2v/).

My research has been supported by the [College of Arts and Sciences](https://www.luc.edu/cas/), by the [Office of the Provost](https://www.luc.edu/academicaffairs/index.shtml), and by the [National Science Foundation](https://www.nsf.gov/).

I am the co-advisor of the LUC SIAM Student Chapter. See more information about the chapter [here](https://loyolachicagosiam.github.io/).

**Visitor Count:**  
<span id="visitor-counter">Loading...</span>

<script>
// GitHub API setup
const repo = 'xiangwanmath/xiangwanmath.github.ioO'; 
const filePath = 'assets/visit_count.json';  
const token = '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';       

async function fetchCounter() {
  try {
    // Fetch current count (no write permissions needed)
    const response = await fetch(`https://api.github.com/repos/${repo}/contents/${filePath}`, {
      headers: { 'Authorization': `token ${token}` },
    });
    const data = await response.json();
    const content = JSON.parse(atob(data.content));
    document.getElementById('visitor-counter').textContent = content.count;
  } catch (error) {
    console.error('Error fetching counter:', error);
    document.getElementById('visitor-counter').textContent = 'Error';
  }
}

fetchCounter();
</script>
