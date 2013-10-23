
<!-- We got time to show some code ?  -->

#Code examples

* Generate your project - code has heaps of comments, turn stuff off as needed.

        padrino-gen project
        Usage:
          padrino-gen project [name] [options]

        Options (edited)
          -a, [--adapter=ADAPTER]                    # SQL adapter for ORM (sqlite, mysql, mysql2, mysql-gem, postgres)
          -p, [--template=TEMPLATE]                  # Generate project from template
          -d, [--orm=ORM]                            # The database engine component (activerecord, minirecord, datamapper, mongomapper, mongoid, sequel, couchrest, ohm, mongomatic, ripple, none)
                                                     # Default: none
          -t, [--test=TEST]                          # The testing framework component (rspec, shoulda, cucumber, bacon, testspec, riot, minitest, none)
                                                     # Default: none
          -m, [--mock=MOCK]                          # The mocking library component (mocha, rr, none)
                                                     # Default: none
          -s, [--script=SCRIPT]                      # The javascript library component (jquery, prototype, rightjs, mootools, extcore, dojo, none)
                                                     # Default: none
          -e, [--renderer=RENDERER]                  # The template engine component (haml, erb, liquid, slim, none)
                                                     # Default: slim
          -c, [--stylesheet=STYLESHEET]              # The stylesheet engine component (less, sass, compass, scss, none)
                                                     # Default: none



##Or just include padrino modules from a Sinatra project

  * form helpers - i do this a bit
