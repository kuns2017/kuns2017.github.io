---
title: "Javascript 성능체크"
date: 2018-12-20 16:16:00 -0400
categories: javascript
---

var fn_test = ()=>{
  var t0 = performance.now();
  console.log("start : " + t0 + 'ms')
  //로직
  
  var t1 = performance.now();
  console.log("end : " + (t1 - t0) + 'ms')
}
