---
layout: archive
title: "Support"
permalink: /support/
author_profile: true
---

We are deeply grateful to our sponsors and supporting partners, whose contributions made this event possible and accessible to a wider audience.

CMSC 2026 is developed in collaboration with **MATHEMATICS WITHOUT BORDERS**, an international education equity initiative sponsored by the [Rotary Club of Taree, District 9660](https://www.tareerotary.org.au), and designed to improve access to computational thinking and STEM education for underrepresented groups, particularly women, early-career researchers, and participants from developing countries. If you want to support the initiative, have a look [here](https://directory.rawcs.com.au/89-2025-26).

For any further information, please contact the Organizing Chairs at [cmsc2026@dei.unipd.it](mailto:cmsc2026@dei.unipd.it).

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
          <img src="{{ sponsor.logo | relative_url }}" alt="{{ sponsor.name }} logo" style="max-width:200px;" />
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
        <a href="{{ sponsor.url }}" target="_blank" rel="noopener"> {{ sponsor.name }} </a><br/>
        <!-- <a href="{{ sponsor.url }}" target="_blank" rel="noopener">
          <img src="{{ sponsor.logo | relative_url }}" alt="{{ sponsor.name }} logo" style="max-height:96px;" />
        </a> -->
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