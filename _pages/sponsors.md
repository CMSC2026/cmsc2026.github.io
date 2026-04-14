---
layout: archive
title: "Sponsors"
permalink: /sponsors/
author_profile: true
---

We are deeply grateful to our sponsors and supporting partners, whose contributions made this event possible and accessible to a wider audience.

If you want to support CMSC 2026, please contact the Organizing Chairs at [cmsc2026@dei.unipd.it](mailto:cmsc2026@dei.unipd.it).


## Sponsors

<table cellspacing="0" cellpadding="0" class="sponsor-table">
  <thead>
    <tr>
      <th class="sr-only">Logo</th>
      <th class="sr-only">Description</th>
    </tr>
  </thead>
  <tbody>
    {% for sponsor in site.data.sponsors %}
    <tr>
      <td>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener" class="visually-hidden"> {{ sponsor.name }} </a><br/>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener">
          <img src="{{ sponsor.logo | relative_url }}" alt="{{ sponsor.name }} logo" style="max-height:128px;" />
        </a>
      </td>
      <!--
      <td>
        <strong><a href="{{ sponsor.url }}" target="_blank" rel="noopener">{{ sponsor.name }}</a></strong><br/>
        {{ sponsor.description }}
      </td>
      -->
    </tr>
    {% endfor %}
  </tbody>
</table>

## Supporting Partners 

<table cellspacing="0" cellpadding="0" class="sponsor-table">
  <thead>
    <tr>
      <th class="sr-only">Logo</th>
      <th class="sr-only">Description</th>
    </tr>
  </thead>
  <tbody>
    {% for sponsor in site.data.supporting_partners %}
    <tr>
      <td>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener" class="visually-hidden"> {{ sponsor.name }} </a><br/>
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener">
          <img src="{{ sponsor.logo | relative_url }}" alt="{{ sponsor.name }} logo" style="max-height:96px;" />
        </a>
      </td>
      <!--
      <td>
        <strong><a href="{{ sponsor.url }}" target="_blank" rel="noopener">{{ sponsor.name }}</a></strong><br/>
        {{ sponsor.description }}
      </td>
      -->
    </tr>
    {% endfor %}
  </tbody>
</table>