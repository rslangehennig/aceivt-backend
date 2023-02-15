I created a freestyle project and installed the UCD publisher plugin and a plugin that allowed me to update the build number.

#!/bin/bash
pwd
ls -al
source '/downloads/ace-developer/ace-12.0.7.0/server/bin/mqsiprofile'
#ibmint package --input-path . --output-bar aceivt.bar --project JGRACEIVT
ibmint package --input-path . --output-bar jgr-cp4i-aceivt.bar
