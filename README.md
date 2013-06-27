bootstrap-customization
=======================

Customizing Twitter Bootstrap 3.0.0

The next upcoming release of [Twitter Bootstrap](https://github.com/twitter/bootstrap "Twitter Bootstrap") will be a strong rewrite of the framework, with the *mobile first* approach.

They added `sm`, `md` and `lg` CSS classes, to identify respectively small, medium and large devices.

In this customization, there is also a fourth CSS class `wd`, to identify wide devices.

You can use this code

    <div class="row">
      <div class="col-lg-3">

        <div class="visible-sm">Visible small</div>
        <div class="hidden-sm">Hidden small</div>

      </div>
      <div class="col-lg-3">

        <div class="visible-md">Visible medium</div>
        <div class="hidden-md">Hidden medium</div>

      </div>
      <div class="col-lg-3">

        <div class="visible-lg">Visible large</div>
        <div class="hidden-lg">Hidden large</div>

      </div>
      <div class="col-lg-3">

        <div class="visible-wd">Visible wide</div>
        <div class="hidden-wd">Hidden wide</div>

      </div>
    </div>

To test those classes.

You can use these media queries to customize your CCS3 rules.

    /* Small to Wide */

    /* Small only */
    @media (max-width: 767px) {

    }

    /* Medium to Large (and larger) */
    @media (min-width: 768px) {

    }

    /* Large to Wide (and larger) */
    @media (min-width: 992px) {

    }

    /* Wide and larger */
    @media (min-width: 1200px) {

    }
