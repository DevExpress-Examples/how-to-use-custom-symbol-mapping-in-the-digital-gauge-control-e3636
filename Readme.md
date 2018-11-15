<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/DigitalGauge_CustomSymbolMapping/MainPage.xaml) (VB: [MainPage.xaml](./VB/DigitalGauge_CustomSymbolMapping/MainPage.xaml))
<!-- default file list end -->
# How to use custom symbol mapping in the Digital Gauge control 


<p>This example demonstrates how to display custom characters on a Digital Gauge control. This is done via the Custom Symbol Mapping feature that defines which segments should be activated for every custom character.</p><p>In this sample we will display "HELLO." using the <strong>7 Segment View</strong> type. Note that by default these characters can't be displayed in this view (because 7 segments are not enough to provide unique representations for all Latin characters), but some characters can be efficiently displayed via custom symbol mapping.</p><br />



<h3>Description</h3>

<p>For this, it is necessary to use the <strong>SymbolSegmentsMapping.SegmentsStates</strong> property to specify appropriate segment states for every desired character. In our case, these will be the following characters: &quot;H&quot;, &quot;E&quot;, &quot;L&quot;, &quot;O&quot;, &quot;.&quot; Note that for the dot character we set the<strong> SymbolType</strong> property value to <strong>Additional</strong>, so that it will be displayed in the same segment with the previous character.</p><p>Then we specify the text that should be displayed on the segments panel via the <strong>DigitalGaugeControl.Text</strong> property.</p><br />


<br/>


