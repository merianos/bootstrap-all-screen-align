# Bootstrap All Screen Align

This is a simple SASS script that producing CSS classes for text alignment in different screen
sizes primarily for bootstrap but of course can be used in other scripts as well.

###Properties

 - **$screens** : A list with the all screen size break points. (*should contain the same amount of elements as $sizes*)
 - **$sizes** : The screen size as used in bootstrap. (*should contain the same amount of elements as $screens*)
 - **$aligns** : The text alignment properties you like to use
 - **$count** : An internal counter for extracting the *nth* element of the sizes array. (*should be always zero*)

###Usage

When you like to use the same alignment for every screen size, you should use the bootstrap default text alignment classes.

#####Example
```html
<p class="text-justify">
Agitabilis sectamque congeriem locavit. Opifex prima terrae aeris fronde locum homini aere habitabilis. Deducite madescit foret.
</p>
```

if, for example, you like to have specific text alignment for a screen sizes bigger than medium size you should first setup the default alignment for the extra small and then for the medium screen like the example tha following:

#####Example
```html
<p class="text-left text-md-center">
Agitabilis sectamque congeriem locavit. Opifex prima terrae aeris fronde locum homini aere habitabilis. Deducite madescit foret.
</p>
```


