---
layout: post
title: Touchegg gestos multitouch en Ubuntu y derivados
date: 2014-01-24
author: neoranger
comments: true
categories: [Informacion]
---
<div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;">¿Has querido alguna vez hacer gestos multitouch en tu distro Linux? bueno, <a href="https://code.google.com/p/touchegg/" style="border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;vertical-align:baseline;">To﻿u﻿chégg</a> pretende hacer eso realidad, de hecho es un proyecto que ya funciona bastante bien y <strong style="border:0;font-size:inherit;font-style:inherit;font-variant:inherit;line-height:inherit;margin:0;padding:0;vertical-align:baseline;">con resultados sorprendentes en el caso de Kubuntu usando el Magic Trackpad de Apple,</strong> y que ahora además, acaba de agregar una interfaz gráfica para su configuración, un gran paso que sin duda facilitará aun más su adopción.</span></div><div style="background-color:white;border:0;color:#444444;font-family:Arial, Helvetica, sans-serif;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><a class="highslide" href="http://www.muylinux.com/2011/03/15/touchegg-gestos-multitouch-en-ubuntu-y-pronto-para-todo-linux/touchegg-1/" rel="attachment wp-att-16146" style="-webkit-transition:.2s ease;border:0;color:#ff7900;font-family:inherit;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;transition:.2s ease;vertical-align:baseline;"><img alt="Touchégg, gestos multitouch para Linux [Actualizado]" class="aligncenter size-medium wp-image-16146" height="452" src="http://www.muylinux.com/wp-content/uploads/2011/03/touchegg-1-500x452.jpg" title="touchegg 1 500x452" width="500" /></a></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;">Touchégg está siendo desarrollado por José Expósito, estudiante de ingeniería que también está desarrollando un gestor ligero de ventanas llamado <a href="http://code.google.com/p/eggwm/" style="border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;vertical-align:baseline;">EggWM</a>, basado en X11 y Qt (y al que seguramente daremos un vistazo más adelante). Aunque la idea originalmente era usar Touchégg en EggWM, el autor ahora pretende<strong style="border:0;font-size:inherit;font-style:inherit;font-variant:inherit;line-height:inherit;margin:0;padding:0;vertical-align:baseline;"> llevar los gestos multitouch a todas las distros Linux</strong> e incluso a BSD.</span></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;">El programa esta hecho en C++ y Qt y utiliza las bibliotecas uTouch-geis, sin embargo depende de evdev y de uTouch para su funcionamiento lo que hace que <strong style="border:0;font-size:inherit;font-style:inherit;font-variant:inherit;line-height:inherit;margin:0;padding:0;vertical-align:baseline;">por ahora sea más fácil de instalar y ejecutar en Ubuntu (y derivados) a partir de su versión 10.10</strong>. De todas maneras, los resultados son muy prometedores como se puede ver en el siguiente vídeo y es cosa de tiempo para que llegue a todo escritorio basado en X11 y compatible con Qt4.</span></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;text-align:center;vertical-align:baseline;"></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;">Para instalar y probar este genial desarrollo en Ubuntu, debes primero asegurarte de que el touchpad de tu portátil (o trackpad externo) soporta el uso de gestos multitouch y luego debes instalar tanto uTouch como evdev de los cuales depende el programa, una vez listo eso, puedes <strong style="border:0;font-size:inherit;font-style:inherit;font-variant:inherit;line-height:inherit;margin:0;padding:0;vertical-align:baseline;">descargar e instalar los paquetes .DEB de TouchEgg y TouchEgg GUI</strong> desde la <a href="https://code.google.com/p/touchegg/wiki/Downloads?tm=2" style="-webkit-transition:.2s ease;border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;transition:.2s ease;vertical-align:baseline;">página de descargas</a> de la aplicación y por último debes seguir <a href="https://code.google.com/p/touchegg/wiki/ConfigureDevices" style="-webkit-transition:.2s ease;border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;transition:.2s ease;vertical-align:baseline;">éstas instrucciones</a> para configurar tu touchpad.</span></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;">Aunque actualmente no funciona en todos los touchpad, sin duda que es <strong style="border:0;font-size:inherit;font-style:inherit;font-variant:inherit;line-height:inherit;margin:0;padding:0;vertical-align:baseline;">otro gran paso en el uso de interfaces en GNU/Linux,</strong> que esperamos, esté disponible para cada escritorio libre. Después de todo, si por algo se han destacado los entornos Linux todos estos años es por su flexibilidad y enormes posibilidades de configuración y personalización, así que opciones, bienvenidas sean.</span></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;"><strong style="border:0;font-size:inherit;font-style:inherit;font-variant:inherit;line-height:inherit;margin:0;padding:0;vertical-align:baseline;">Actualización:</strong> Tal como lo mencionaba Malcer y el mismo José, para usarlo en otras distros Linux se necesitan las mismas dependencias ya señaladas (Qt, evdev y uTouch) y <a href="https://code.google.com/p/touchegg/wiki/CompileSourceCode" style="border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;vertical-align:baseline;">compilar</a> el código fuente que puedes descargar desde la <a href="https://code.google.com/p/touchegg/wiki/Downloads?tm=2" style="border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;vertical-align:baseline;">página descargas</a> y luego configurar según las <a href="https://code.google.com/p/touchegg/wiki/ConfigureDevices" style="border:0;color:#ff7900;font-size:inherit;font-style:inherit;font-variant:inherit;font-weight:inherit;line-height:inherit;margin:0;outline:0;padding:0;text-decoration:none;vertical-align:baseline;">instrucciones</a>. </span></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;"><br /></span></div><div style="background-color:white;border:0;color:#444444;font-size:14px;line-height:21.979999542236px;margin-bottom:14px;padding:0;vertical-align:baseline;"><span style="font-family:Helvetica Neue, Arial, Helvetica, sans-serif;"><a href="http://www.muylinux.com/2011/03/15/touchegg-gestos-multitouch-en-ubuntu-y-pronto-para-todo-linux" target="_blank">FUENTE</a></span></div>