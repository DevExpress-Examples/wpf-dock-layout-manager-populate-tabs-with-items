# How to: Display Items in Tabs


<p>The DXDocking suite provides several approaches to display content in tabs. For this, you can use either of the following containers</p>
<p>- A <a href="https://documentation.devexpress.com/#WPF/CustomDocument6824">LayoutGroup </a>with <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDockingLayoutGroup_GroupBorderStyletopic">GroupBorderStyle</a> set to <strong>Tabbed</strong>;<br>- A <a href="https://documentation.devexpress.com/#WPF/CustomDocument6825">TabbedGroup</a>;<br>- A <a href="https://documentation.devexpress.com/#WPF/CustomDocument6830">DocumentGroup</a>.</p>
<p>In this example, we demonstrated all three approaches.</p>
<p><br>Although all these groups allow displaying tabs, they are designed for use in different scenarios.<br>A DocumentGroup will be the best choice if the task is to display dynamic content. It works similar to the document area in the Visual Studio.</p>
<p><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-display-items-in-tabs-t326792/15.1.3+/media/cdfa2c50-a7ba-11e5-80bf-00155d62480c.png"></p>
<p>A TabbedGroup is designed to display more static content like toolbars, service information, etc.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-display-items-in-tabs-t326792/15.1.3+/media/e2d07c56-a7ba-11e5-80bf-00155d62480c.png"></p>
<p>A LayoutGroup with the Tabbed style is intended to display a static set of elements. Unlike DocumentGroup and TabbedGroup, it supports moving tabs only in <a href="https://documentation.devexpress.com/#WPF/CustomDocument7222">customization mode</a>.</p>

<br/>


