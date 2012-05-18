JQuery-Library
==============

&lt;acre:script>  var t = acre.require("/freebase/libs/jquery/templates"); &lt;/acre:script> &lt;html>  &lt;head>    &lt;title>whatever&lt;/title>    ${t.jquery()}                   &lt;!-- tell browser to load jquery -->    ${t.jquery_ui('smoothness')}    &lt;!-- tell browser to load jquery UI with the given theme (and all required css files) -->    ${t.jquery_plugin('cookie')}    &lt;!-- tell browser to load a jquery plugin -->    ${t.underscore()}               &lt;!-- tell browser to load underscore -->  &lt;/head>  &lt;body>    ...  &lt;/body> &lt;/html>