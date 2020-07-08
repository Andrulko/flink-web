---
title: "Stateful Computations over Data Streams"
layout: base
---

<div class="row-fluid">

  <div class="col-sm-12">
    <p class="lead" markdown="span">
      **Apache Flink<sup>®</sup> — Stateful Computations over Data Streams**
    </p>
  </div>

<div class="col-sm-12">
  <hr />
</div>

</div>

<!-- High-level architecture figure -->

<div class="row front-graphic">
  <hr />
  <img src="{{ site.baseurl }}/img/flink-home-graphic.png" width="800px" />
</div>

<!-- Feature grid -->

<!--
<div class="row">
  <div class="col-sm-12">
    <hr />
    <h2><a href="{{ site.baseurl }}/features.html">Features</a></h2>
  </div>
</div>
-->
<div class="row">
  <div class="col-sm-4">
    <div class="panel panel-default">
      <div class="panel-heading">
        <span class="glyphicon glyphicon-th"></span> <b>All streaming use cases</b>
      </div>
      <div class="panel-body">
        <ul style="font-size: small;">
          <li>Event-driven Applications</li>
          <li>Stream &amp; Batch Analytics</li>
          <li>Data Pipelines &amp; ETL</li>
        </ul>
        <a href="{{ site.baseurl }}/usecases.html">Learn more</a>
      </div>
    </div>
  </div>
  <div class="col-sm-4">
    <div class="panel panel-default">
      <div class="panel-heading">
        <span class="glyphicon glyphicon-ok"></span> <b>Guaranteed correctness</b>
      </div>
      <div class="panel-body">
        <ul style="font-size: small;">
          <li>Exactly-once state consistency</li>
          <li>Event-time processing</li>
          <li>Sophisticated late data handling</li>
        </ul>
        <a href="{{ site.baseurl }}/flink-applications.html#building-blocks-for-streaming-applications">Learn more</a>
      </div>
    </div>
  </div>
  <div class="col-sm-4">
    <div class="panel panel-default">
      <div class="panel-heading">
        <span class="glyphicon glyphicon glyphicon-sort-by-attributes"></span> <b>Layered APIs</b>
      </div>
      <div class="panel-body">
        <ul style="font-size: small;">
          <li>SQL on Stream &amp; Batch Data</li>
          <li>DataStream API &amp; DataSet API</li>
          <li>ProcessFunction (Time &amp; State)</li>
        </ul>
        <a href="{{ site.baseurl }}/flink-applications.html#layered-apis">Learn more</a>
      </div>
    </div>
  </div>
</div>
<div class="row">
  <div class="col-sm-4">
    <div class="panel panel-default">
      <div class="panel-heading">
        <span class="glyphicon glyphicon-dashboard"></span> <b>Operational Focus</b>
      </div>
      <div class="panel-body">
        <ul style="font-size: small;">
          <li>Flexible deployment</li>
          <li>High-availability setup</li>
          <li>Savepoints</li>
        </ul>
        <a href="{{ site.baseurl }}/flink-operations.html">Learn more</a>
      </div>
    </div>
  </div>
  <div class="col-sm-4">
    <div class="panel panel-default">
      <div class="panel-heading">
        <span class="glyphicon glyphicon-fullscreen"></span> <b>Scales to any use case</b>
      </div>
      <div class="panel-body">
        <ul style="font-size: small;">
          <li>Scale-out architecture</li>
          <li>Support for very large state</li>
          <li>Incremental checkpointing</li>
        </ul>
        <a href="{{ site.baseurl }}/flink-architecture.html#run-applications-at-any-scale">Learn more</a>
      </div>
    </div>
  </div>
  <div class="col-sm-4">
    <div class="panel panel-default">
      <div class="panel-heading">
        <span class="glyphicon glyphicon-flash"></span> <b>Excellent Performance</b>
      </div>
      <div class="panel-body">
        <ul style="font-size: small;">
          <li>Low latency</li>
          <li>High throughput</li>
          <li>In-Memory computing</li>
        </ul>
        <a href="{{ site.baseurl }}/flink-architecture.html#leverage-in-memory-performance">Learn more</a>
      </div>
    </div>
  </div>
</div>

<!-- Powered by section -->

<div class="row">
  <div class="col-sm-12">
    <br />
    <h2><a href="{{ site.baseurl }}/poweredby.html">Powered by Flink</a></h2>

  <div class="jcarousel">
    <ul>
        <li>
          <div><a href="{{ site.baseurl }}/poweredby.html">
            <img src="{{ site.baseurl }}/img/poweredby/alibaba-logo.png" width="175"  alt="Alibaba" />
          </a></div>!!crwd_CB_2_BC_dwrc!!  </div>

  <a href="#" class="jcarousel-control-prev" data-jcarouselcontrol="true"><span class="glyphicon glyphicon-chevron-left"></span></a>
  <a href="#" class="jcarousel-control-next" data-jcarouselcontrol="true"><span class="glyphicon glyphicon-chevron-right"></span></a>

  </div>

</div>

<!-- Events section -->
<div class="row">

<div class="col-sm-12">
  <hr />
</div>

<div class="col-sm-3">

  <h2><a>Upcoming Events</a></h2>

</div>
<div class="col-sm-9">
  <!-- Flink Forward -->
  <a href="https://flink-forward.org" target="_blank">
    <img style="width: 200px; padding-right: 30px" src="{{ site.baseurl }}/img/flink-forward.png" alt="Flink Forward"/>
  </a>
  <!-- ApacheCon -->
  <a href="https://www.apache.org/events/current-event" target="_blank">
    <img src="https://www.apache.org/events/current-event-234x60.png" alt="ApacheCon"/>
  </a>
</div>

</div>

<!-- Updates section -->

<div class="row">

<div class="col-sm-12">
  <hr />
</div>

<div class="col-sm-3">

  <h2><a href="{{ site.baseurl }}/blog">Latest Blog Posts</a></h2>

</div>

<div class="col-sm-9">

  <dl>
    {% for post in site.posts limit:5 %}  
        <dt> <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></dt>
        <dd>{{ post.excerpt }}</dd>
    {% endfor %}
  </dl>

</div>

<!-- Scripts section -->

<script type="text/javascript" src="{{ site.baseurl }}/js/jquery.jcarousel.min.js"></script>

<script type="text/javascript">

  $(window).load(function(){
   $(function() {
        var jcarousel = $('.jcarousel');!!crwd_CB_3_BC_dwrc!!  });

</script>
