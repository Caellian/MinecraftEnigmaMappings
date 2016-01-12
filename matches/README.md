# Contents
This folder contains most if not all *.matches files I created while upgrading/downgrading Minecraft mappings. They are here in case someone finds them useful.
You can add your own matches, but make sure they are complete or mark them as incomplete as shown below.

# Naming
Name of *.matches files starts with game side ("s" or "c") and input Minecraft version, followed by an arrow ("->") indicating transition from first version to last one, after the arrow comes output Minecraft version followed by either "-cm" (class matches), "-fm" (field matches) or "-mm" (method matches). If mappings are not complete, they have to be prefixed with "[WIP]". Every file should end with lowercase ".matches" extension.

Examples:
- "[WIP]c1.8->15w51b-cm.matches"
- "s1.8.4->1.8.5-fm.matches"
- "c1.7.10->1.8.3-cm.matches"

*NOTE: At current state, enigma doesn't seem to be capable of generating field matches or method matches - they also don't seem needed.*
