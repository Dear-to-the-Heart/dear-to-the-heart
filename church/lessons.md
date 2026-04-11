---
layout: page
title: Teaching Resources
page_title: Teaching Resources
description: Ideas and Strategies for an<br/>Inclusive Church Classroom
include_nav: true
---

<style>
  #lessons {
    margin-bottom: 80px;
  }
  #lessons iframe {
    float: right;
  }
  #lessons > div {
    margin-bottom: 20px;
    font-weight: bold; 
  }
  #lessons a.icon {
    display: inline-block;
    margin-left: 10px;
    font-size: 30px;
    vertical-align: middle;
  }
  #lessons table tr:hover td {
    background: #eee;
  }
  #lessons table tr td:first-of-type img {
    width: 150px;
    height: 150px;
    object-fit: contain;
    object-position: center;
  }
  #lessons table tr.small td {
    font-size: 13px;
    line-height: 18px;
    padding: 5px;
  }
  #lessons table tr.small td:first-of-type {
    text-align: center;
  }
  #lessons table tr.small td:first-of-type img {
    width: 50px;
    height: 50px;
  }
  #lessons table tr td {
    vertical-align: middle;
  }
</style>
<h2>Inclusive Come Follow Me</h2>

The Church encourages inclusion rather than separate
disability classrooms or ministries. This means that your classroom has the
potential to be the most inclusive place some of your students 
experience each week. If you take a few minutes to prepare with them
in mind, and direct a portion of your lesson toward their personal
growth, you will already be ahead of what most people with disabilities
experience in their school and community. But let's not stop there!

<h3>Weekly Lessons</h3>

<p>The Come Follow Me lessons are a great way to organize and prepare for
  teaching in church. If you don't have a lot of practice supporting people
  with disabilities, then you may need additional resources than what's 
  available in Gospel Library. Worry not! We have activity and discussion
  ideas that can help make sure your classroom is inclusive while
  still supporting *all* of your students.
</p>
<div id='lessons'>
  <table style='display: inline-block; width: 600px;'>
  </table>
</div>
<div style='clear: both;'></div>
<script>
  var elem = document.getElementById('lessons');
  var preview = (window.lessons || []).find(function(e) { return e .insta; });
  if(preview) {
    var iframe = document.createElement('iframe');
    iframe.src = preview.insta + '/embed';
    iframe.classList.add('instabox');
    iframe.setAttribute('frameborder', '0');
    elem.appendChild(iframe);
  }
  var cnt = 0;
  lessons.forEach(function(lesson) {
    var div = document.createElement('tr');
    var td = document.createElement('td');
    var img = document.createElement('img');
    img.src = lesson.img || "/dear-heart.400.png";
    td.appendChild(img);
    div.appendChild(td);

    td = document.createElement('td');
    var a = document.createElement('a');
    a.setAttribute('href', lesson.url);
    a.innerText = lesson.title;
    td.appendChild(a);
    div.appendChild(td);

    td = document.createElement('td');
    if(lesson.insta) {
      a = document.createElement('a');
      a.classList.add('icon');
      a.classList.add('fa-instagram');
      a.setAttribute('href', lesson.insta);
      td.appendChild(a);
    }
    div.appendChild(td);
    if(cnt > 5) {
      div.classList.add('small');
    }
    elem.querySelector('table').appendChild(div);
    cnt++;
  });
</script>

<h3>Teaching Strategies</h3>

<iframe src="https://www.instagram.com/reel/DNWj5UISScX/embed" frameborder=0 class='instabox' style='float: right; margin-left: 10px;'></iframe>

<a href="https://docs.google.com/document/d/1RamoGX_pDv9aIlCqa2GZWyA_oYz7flJJX2RebxTrq5E/edit?usp=sharing">Disability Teaching in Church</a> is a structured approach to improving your classroom teaching in a way
that will benefit all your students, including those with disabilities. It includes a research-based sequence of strategies you can try on your own schedule, links to
video examples, and tools to help you track your efforts and progress.

<div style='clear: both;'></div>