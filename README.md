# collapsible-menu

Collapsible Menu Guide using jQuery

1. Open the file collapsible-menu-template-JQUERY.html and paste into the content/html area of your page.

2. Paste the following script into Javascript section on the page - choose the position:after content //// if there is no Javascript area for where you are adding this then adding it to the bottom of the HTML file will work.

      <script>
      $(function(){
          $('.my-collapsible-tab').click(function(){
              $('.my-collapsible-tab-content').slideUp();
              $('.my-collapsible-tab-content').hide();
              $('#mycollapsibletab'+$(this).attr('target')).slideToggle();
          });
      });
      </script>


*NOTE - make sure to include the opening and closing <script> tags!
