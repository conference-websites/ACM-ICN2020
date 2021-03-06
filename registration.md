---
layout: default
title: Registration Information

registrations:
  fees:
    - type: Conference Registration
      price: ["$40", "$50"]
    - type: Student Registration
      price: ["Free", "$20"]
---

## Registration Information

<div class="border ui-corner-all ui-shadow">
  <table class="sponsorlevels">
    <tbody>
      <tr>
        <th style="text-align:left"></th>
        <th>ACM Member</th>
        <th>Non-Member</th>
      </tr>
      {% for reg in page.registrations.fees %}
      <tr>
        <th style="text-align:left">{{ reg.type }}</th>
        <td> {{ reg.price[0] }} </td>
        <td> {{ reg.price[1] }} </td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
</div>


[Online registration](https://www.cvent.com/d/r7qs8b){: data-role="button" class="button" }

In case of problems with registration or billing, please contact [Registration Chair](mailto:icn202x@gmail.com).


### A Special Note on Author Registration Policy

- Each accepted full-paper/short-paper/workshop-paper/poster/demo must be accompanied by a Conference Registration. Each Conference Registration can cover multiple full papers, short papers, osters, or demos.

- Each accepted full-paper/short-paper/workshop-paper/poster/demo must provide pre-recording **and** <u>be virtually presented by one of its author(s) at the conference</u>. The presenting author(s) must be registered for the conference.

- Registration accepts Visa, MasterCard, American Express.
