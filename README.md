## Amazon Web Services for Prowl 

This is documentaiton in regards to how we are using Prowl with AWS.

## Amazon QuickSight

QuickSight is from the AWS suite that is simply a tool to visually build ad-hoc queries. As of now, there is no API for it so that we can automatically generate dashboards and there is no built in way to run statistical testing. For this, we can use Plotly, or something similar.

## Vagrant 

In the private Prowl repo's there are some VMWare Fusion license keys "add-ons" for Vagrant, worth about $70 a piece, still available if anyone involved in Prowl needs a key. We will be using precompiled Gentoo boxes for most testing via Vagrant. https://gentoo.org/

You can access this box, that's maintained by myself (Montana) via 

<pre>vagarant init montana/gentoo64</pre>
<pre>vagrant up</pre>
<pre>vagrant ssh</pre> 

If there is a port collision, I've already released a patch for this box, so port collisions should be fixed. 
