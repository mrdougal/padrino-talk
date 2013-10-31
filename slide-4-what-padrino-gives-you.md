
#What Padrino gives you

<!-- Some/most of the functionality that you've started to miss -->


* Form Helpers  - form_tag, form_for, field_set_tag
* Tag Helpers   - tag, content_tag, input_tag.
* Asset Helpers - link_to, image_tag
* Text Helpers  - "Useful formatting" relative_time_ago, js_escape_html

* Mailer       - Similar to ActionMailer (uses Mail gem)
* Caching      - Route and fragment caching <!-- rails takes it away -->
* Localization - I18n just like Rails <!-- defined as yaml -->


<!-- 
  these are all modules, so you pick what you want 
  if you include all of these you basically have rails - issue
-->


##Generators
  * applications
  * models
  * controllers
  
<!-- handy to get you going, or how to configure a large sinatra app -->


<!-- Handy but not hard to add into a Sinatra project -->

* Logging   - Unified logger
* Reloading - Reloads code during development

<!-- Also it has an admin interface, with authentication - never used it -->


#Features that extend Sinatra


* Routing
    * Full url named routes
    * Named params
    * Respond_to support
    * before/after filters
    
    <!-- if have the time will show some samples -->
    
    
* Mountable - Mounting multiple apps 
<!-- can do this in rack - padrino makes it easy -->

