---
title: Eine Simulation ausführen
---
{% raw %}
<section><h1>Diskrete Ereignis-Simulationen</h1>

    <p>... are computational models of real-world systems conceived as <em>discrete dynamic systems</em> by representing
     their state with the help of <em>state variables</em> (in the form of attributes of object types), and capturing
     their dynamics by modeling the events that are responsible for their <em>state changes</em>. Typically, they use
     <em>next-event</em> time progression (as opposed to <em>fixed-increment</em> time progression).</p>

    <p>Go to <a href="../des-models/index.html">Discrete Event Simulations</a>.</p>
    </section>

    <section><h1>Processing Network Models</h1>

    <p>... are an important class of Discrete Event Simulations, where objects enter a system via <em>arrival</em> events at an <em>entry node</em> and then flow through one or more <em>processing nodes</em> (representing, e.g., sevice desks or manufacturing machines) where they are subject to processing activities before they leave the system at an <em>exit node</em> via <em>departure</em> events. These models are the focus of most comercial simulation tools, such as <em>Arena</em>, <em>Simio</em> and <em>AnyLogic</em>.</p>

    <p>Go to <a href="../pn-models/index.html">Processing Network Models</a>.</p>
    </section>

    <section><h1>Grid Space Models</h1>

    <p>... are widely used in the social sciences, and are often implemented with the simulation programming framework <a href="http://ccl.northwestern.edu/netlogo/index.shtml">NetLogo</a>. They use the two-dimensional discrete Euclidean space, called <em>grid space</em>, for visualizing simulation runs. Typically, they use <em>discrete </em>simulation time and <em>fixed-increment </em>time progression (as opposed to <em>next-event </em>time progression). A grid space model that does neither define objects nor events, but only grid cell states and grid cell state changes based on the states of neighbor cells, may be considered a <em><strong>Cellular Automata</strong></em> model.</p>

    <p>Go to <a href="../gridspace-models/index.html">Grid Space Models</a>.</p>
    </section>

    <section><h1>Agent-Based Simulations</h1>

    <p>are currently not yet, but will soon be, supported by Sim4edu.</p>
    </section>

    <section><h1 id="ContSim">Continuous Simulations</h1>

    <p>... are mainly used in science and enginering. They model the spatial structure and continuous state changes of objects and matter. They use <em>continuous </em>simulation time with <em>fixed-increment </em>time progression.</p>

    <p>Go to <a href="../continuous-models/index.html">Continuous Simulation Models</a>.</p>
    </section>
  {% endraw %}