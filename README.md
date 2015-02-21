curveapi
========

Implementation of various mathematical curves that define themselves over
a set of control points. The API is written in Java. The curves supported
are: Bezier, B-Spline, Cardinal Spline, Catmull-Rom Spline, Lagrange,
Natural Cubic Spline, and NURBS.

About this project
------------------

This is a mavenized version of http://sourceforge.net/projects/curves . This
is not quite a fork -- as I do not intend to change/improve the project.
However, bugfixes and reasonably scoped improvements will be accepted.


List of changes
---------------

* The javadocs have been removed from this distribution
* The build scripts have been removed and pom.xml has been added to support
  usage with maven
* sun.awt.geom.Curve has been copied from OpenJDK to remove dependency on
  JDK internals

Licenses
--------

The original project used a BSD license, and remains so.

com.graphbuilder.sun.awt.geom.Curve is licensed under GPLv2 with classpath
exception.

