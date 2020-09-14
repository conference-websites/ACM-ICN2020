---
layout: default
title: Registration Information

registrations:
  fees:
    - type: Author Registration (1 author/paper)
      price: ["$150", "$150"]
    - type: Non-Author Registration
      price: ["$50", "$40"]
    - type: Non-Author Student Registration
      price: ["$20", "Free"]
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

In case of problems with registration or billing, please contact [Registration Chair](mailto:KimKhoa.Nguyen@etsmtl.ca,marie@mjmontpetit.com).


### A Special Note on Author Registration Policy

- Each accepted full-paper/short-paper/workshop-paper/poster/demo must be accompanied by an Author Registration (not a Non-Author or Non-Author Student Registration). Each Author Registration covers 1 (one) full paper, short paper, workshop paper, poster, or demo.

- Each accepted full-paper/short-paper/workshop-paper/poster/demo must provide pre-recording **and** <u>be virtually presented by one of its author(s) at the conference</u>. The presenting author(s) must be registered for the conference.

- Student registrations require uploading a scanned student ID card or equivalent verification.

- Registration accepts Visa, MasterCard, American Express.
