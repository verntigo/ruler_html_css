INITIAL COMMIT
==============

I found a metric ruler at codepen.io. I modified it for US Customary units.
The originals are ruler_metric.html & ruler_metric.css. My modifications are
ruler_uscust.html & ruler_uscust.css.

The HTML defines the ruler with a nested <div> structure. The CSS performs the
kind of tasks one might normally use Javascript to perform; the programming,
if you will.

The original does all meaurements in percentages. My modifications do the same
in the more internal parts, but the top level ruler has a defined width in
inches. 7 inches, to be specific.

To change the size, shrinking will be the easiest. The best strategy would be
to just set the tags of the ruler lines you don't want to see to "hidden".
Growing is certainly possible, but you would need to recalculate the
percentages for the inch markers.
