
#Padrino != Rails

<!-- 
  * NO "arsehat" pipeline
  * NO turbolinks 
-->


* Functionality similar, syntax may be different
  * "link_to" isn't as flexible <!-- you can't pass it a block -->

* Integration can take more effort <!-- there is no railstie -->
  
* Some gems won't work, they extend rails features
  * Not always a deal breaker <!-- subjective -->
  * Migrate functionality to model layer, or rack


<!-- 
  eg: Device builds on warden, warden lives in rack
      Your business logic is possibly a simple ruby model
 -->



