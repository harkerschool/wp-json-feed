# WP JSON Feed

## Options

### domain
Domain where WP JSON plugin is active. 
Default: 'http://news.harker.org'

### method
Request method of WP JSON. Refer to [plugin's notes on methods](http://wordpress.org/plugins/json-api/other_notes/#2.-Request-methods).
Default: 'get_recent_posts'

### args
Request arguments. Refer to [plugin's notes on arguments](http://wordpress.org/plugins/json-api/other_notes/#3.-Request-arguments).
Default: { date_format: 'F j, Y' }

### container
Container of news feed (either 'ul' or 'div').
Default: 'ul'

### success 
Function to run after feed has been generated.
Default: function() {}