**Notice**

This functionality to going to be developed into the Boostrap tags for ColdFusion project


**FW/1 + Form Utils**

FW/1 was developed by Sean Corfield to be a light weight MVC framework for ColdFusion.

Form Util CFC was created by Brian Kotek to make ColdFusion form processing more sophisticated by converting them to structs and arrays.

FW/1 takes all url.* and form.* variables an combines them into rc.*. Form Util CFC takes all url.* and form.* variables and converts them into structures and arrays.

In order to get both of these to work together, FW/1 requires a small modification to how it builds the rc.* structure.




**FW/1**

This FW/1 directory is a complete web application and expects to live in its own
webroot if you plan to run the applications within it. To use FW/1 in a separate
webroot you can either copy the org directory to that webroot or add a mapping
for /org/corfield to the corfield folder inside the org directory (or a /org
mapping to the org directory directly).

Project home: http://fw1.riaforge.org

Documentation wiki: http://github.com/seancorfield/fw1/wiki

Blog: http://corfield.org/blog/archives.cfm/category/fw1

Support: http://groups.google.com/group/framework-one/


**Form Utils CFC**

<!--- 
LICENSE 
Copyright 2007 Brian Kotek

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
--->

Project home: http://formutils.riaforge.org/


