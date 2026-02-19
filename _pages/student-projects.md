---
layout: page
permalink: /student projects/
title: Student Projects
page_title: Student Projects
description:
nav: true
nav_order: 5
---

<style>
.projects-tabs {
  border: 1px solid #d5d5d5;
  border-radius: 8px;
  padding: 1rem;
  background: #fff;
}

.projects-tabs input[type="radio"] {
  display: none;
}

.projects-tabs label {
  display: inline-block;
  padding: 0.5rem 1rem;
  margin-right: 0.5rem;
  border: 1px solid #d5d5d5;
  border-bottom: none;
  border-top-left-radius: 6px;
  border-top-right-radius: 6px;
  background: #f2f2f2;
  font-weight: 500;
  cursor: pointer;
}

.projects-tabs input[type="radio"]:checked + label {
  background: #fff;
  border-bottom: 1px solid #fff;
}

.projects-tabs .tab-panel {
  display: none;
  border-top: 1px solid #d5d5d5;
  padding-top: 1.5rem;
  margin-top: 0.5rem;
}

#student-projects-2024:checked ~ #student-projects-2024-panel,
#student-projects-2025:checked ~ #student-projects-2025-panel {
  display: block;
}

.projects-tabs .coming-soon {
  background: #f8f8f8;
  padding: 1rem;
  border-radius: 6px;
}
</style>

<div class="projects-tabs">
  <input type="radio" name="student-projects-tab" id="student-projects-2024" checked>
  <label for="student-projects-2024">Student Projects 2024</label>

  <input type="radio" name="student-projects-tab" id="student-projects-2025">
  <label for="student-projects-2025">Student Projects 2025</label>

  <div class="tab-panel" id="student-projects-2024-panel">
    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Coffee.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-coffee-maker">Comparison of coffee brew types: Grounds, K-Cups, Nespresso</a> </h4>
        <p>Authors: Amanda Kosmen, Kayla Tillman, Lena Sylvan, and Saul Verdi </p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Steel.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-timber-steel">Timber vs. Steel Construction LCA</a> </h4>
        <p>Authors: Douglas Aris, Arman Church, Ellie Lind, Luke Simmons </p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Marker.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-chalk-marker">Chalk vs Whiteboard Marker LCA</a> </h4>
        <p>Authors:  Brooke Leber, Chealen Berry, Kyle Yuen, Sydney Astle</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Solar Array.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-solar">EIOLCA of a residential solar array installation</a> </h4>
        <p>Authors:  Jarvis Forbes, Annie Ho, Alex Olechowski, Hector Ontiveros Morales</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Bottle Water .png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-water-bottle">From production to landfill:  The life cycle analysis of a meal swipe Dasani water bottle</a> </h4>
        <p>Authors:  Seeley McGillis, Anna Kovacs, Joselyn Council, Maria Monroy</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Ryan.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-Ryan">Life cycle assessment (LCA) for the “new” Ryan Field</a> </h4>
        <p>Authors:  Jake Arthurs, Joseph Brogan, Evan Popat, Hunter Renner</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/concrete (Sheridan Road).png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-concrete-road">Sheridan Road: Life cycle assessment of concrete</a> </h4>
        <p>Authors: Liv Brown, Adelina Amineva, James Kim, Aya Ibrahim</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Canoe .png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-canoe">Concrete canoe life cycle assessment</a> </h4>
        <p>Authors:  Destiny Lara, Kassie Ramirez, Aimee Sze, Julia Yazhari</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/ozzi.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-ozzi">Ozzi vs. Styrofoam EIOLCA</a> </h4>
        <p>Authors:  Allie Holmgren, Jackson Bremen, William Marchetta, Peter Pinder</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/Book.png" alt="Example Image" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-books">LCA --print books vs e-books</a> </h4>
        <p>Authors:  Brynn Stasiulis and Momodou Senghore</p>
      </div>
    </div>
  </div>

  <div class="tab-panel" id="student-projects-2025-panel">
    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/01_streaming_vs_cd_lca.png" alt="Streaming vs CD LCA" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-streaming-vs-cd">Streaming vs CD LCA</a> </h4>
        <p>Authors: Ezra Danzig, Alvin Huang, Scout Russell, Jonah Turner</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/02_eiolca_home_fragrance.png" alt="Home Fragrance EIOLCA" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-home-fragrance">EIOLCA of Home Fragrance Products</a> </h4>
        <p>Authors: Elena, Evelyn, Mila, Temlandvo, and Will</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/03_eiolca_ev_vs_gas_vehicle.png" alt="Electric vs Gas Vehicles" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-electric-vs-gas">EIOLCA of Electric vs. Gas-Powered Vehicles</a> </h4>
        <p>Authors: Gianna Brogley, Zachary Crampton, Fiona Letsinger, Ryan Short, &amp; Kate Wojciechowski</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/04_electrifying_bus_fleet.png" alt="Bus Fleet Electrification" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-bus-fleet-electrification">Analysis of Electrifying a Bus Fleet</a> </h4>
        <p>Authors: Nathan Foley, David Kim, Jon Myers</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/05_mid_city_transitway_vs_brt_eiolca.png" alt="Mid-City Transitway vs BRT" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-mid-city-transitway">Mid-City Transitway vs. Bus Rapid Transit: A Comprehensive EIOLCA Analysis</a> </h4>
        <p>Authors: Yahya Arastu, Salada Abdullahi, Murad Gawish, Cheney Sang</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/06_grocery_bags_lca.png" alt="Grocery Bags LCA" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-grocery-bags">Grocery Bags Life Cycle Assessment</a> </h4>
        <p>Authors: Evangeline Davis, Nicole Rodriguez, Brianna Edenburn, Anna Schuller</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/07_la_vegas_high_speed_rail.png" alt="LA-Vegas High-Speed Rail" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-la-vegas-high-speed-rail">Evaluating Environmental Impacts and Travel Efficiency of the LA-Vegas High-Speed Rail</a> </h4>
        <p>Authors: Diane Kao, James Lafayette, Leah Kollo, Ronald Glas</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/08_ev_vs_ice.png" alt="EV vs ICE" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-ev-vs-ice">Electric Vehicles (EV) vs. Internal Combustion Engines (ICE)</a> </h4>
        <p>Authors: Ella Salcedo, Michelle Jo, Lianne Kim, &amp; Sophia Jedziniak</p>
      </div>
    </div>

    <br>

    <div style="display: flex; align-items: center;">
      <img src="{{ site.baseurl }}/assets/img/materials/09_intercampus_vs_escooters.png" alt="Intercampus vs E-Scooters" style="margin-right: 20px; max-width: 250px;"/>
      <div>
        <h4><a href="{{ site.baseurl }}/projects-intercampus-vs-escooters">Intercampus vs. E-Scooters</a> </h4>
        <p>Authors: Jomi Babatunde-Omoya, Shreya Sridhar, Michael Wong</p>
      </div>
    </div>
  </div>
</div>
