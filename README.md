# GT-Tools-Bonus
This scripts is my workflow base on https://github.com/TrevisanGMW/gt-tools for convert mixamo or accurig to native gt tools rig.
# Discription
The scripts is using GT Tools biped rigger, export/import weight map (built-in maya), mixamo auto-rigger or accurig auto rigger to function. Only works with humanoid rig type.

Instead of weight paint the body, this scripts help you transfer the weight from auto-rigger (Mixamo or Accurig) to GT Tools rig, to save your time and sanity to deal with other stuff (weight paint the face, or animations, etc...).

<b>The benefits of GT Tools rig instead of using Human IK rig is:</b>
1. Beginner friendly, light weight, good for humanoid rig type.
2. Has a good controller, ik/fk switching, animation export/import, retarget animation library tool, game fbx export, etc...
3. Easy repair with proxy base rig, if somethings wrong, you could:
   + Export weight map, then extract proxy from gt tools rig.
   + Delete the falied rig, import proxy and change position you want.
   + Generate rig, bind skin and import weight map.

<b>This scripts is written by chatgpt through try and error because i don't know how to code, i do test it many times before posted here, but there is no guaranteed you will not encounter any error, if you do so, please restart the code or maya, if it still not working, please re-install maya. You could sumbit the error so i could look into it and fix it (not really sure i could fix or not, but i will try).</b>

<b>The scripts is using shelf button, so i will pack the scripts with .txt format instead of .py format</b>

# How to install
1. First, install GT Tools: "https://github.com/TrevisanGMW/gt-tools"
2. Download this scripts. Extract zip file
3. Go to shelf settings - New shelf - Name it - Ok
4. Open Maya Script Editor - new tab - Python
5. Open txt file, copy all - paste into maya script editor python tab
6. Copy all - press hold Left button mouse, drag the mouse on shelf then release left mouse, choose python
7. Edit the name to easy remember. You done it!

<b>Demonstrated Gif will comming soon!</b>
  
<b>Docs will comming soon!</b>

