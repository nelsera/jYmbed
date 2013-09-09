jYmbed
======

jYmbed is a jQuery simple plugin for embedding a Youtube videos from a url of the video.
It provides a full and flexible toolset for embedding Youtube videos.

Documentation
-------------

### Installation

To use the jYmbed plugin, include the jQuery library and the jCarousel source file into your HTML document:

<script type="text/javascript" src="/path/libs/jquery-1.10.2.min.js"></script>
<script type="text/javascript" src="/path/dist/jquery.jYmbed.js"></script>

To setup jYmbed, add the following code to your HTML document:

<code>
<script>
	$(document).ready(function(){
		$(".youtube").jYmbed();
	});
</script>
</code>

Download
--------

All ready-to-use files are located in the [`dist/`](dist/) directory.

The [`jquery.jYbmed.js`](dist/jquery.jYmbed.js?raw=1) and
[`jquery.jYmbed.min.js`](dist/jquery.jYmbed.min.js?raw=1) files contain
the core and all plugins concenated together.

Examples
--------

You can find some example implementations in the [`examples/`](examples/)
directory.

License
-------

Copyright (c) 2013 Luciano Souza.
Released under the [MIT](LICENSE?raw=1) license.
