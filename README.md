## SVG Target Faces

SVG renderings of typical archery target faces, such as WA 10-zone, 6-zone, triple spot, NFAA 5-zone and AGB Worcester faces.


## Usage

  Please see index.html source code for details.

  Example for a 6-zone WA target face:

    <svg id="svg_wa_6_zone" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" height="100%" width="100%" viewBox="0 0 600 600">

      <g>
        <!-- 5-RING -->
        <circle cx="300" cy="300" r="239" fill="#00B4E4"/>

        <!-- 6-RING -->
        <circle cx="300" cy="300" r="199" fill="#00B4E4" stroke="#000000" stroke-width="1"/>

        <!-- 7-RING -->
        <circle cx="300" cy="300" r="159" fill="#FD1B14" stroke="#000000" stroke-width="1"/>

        <!-- 8-RING -->
        <circle cx="300" cy="300" r="119" fill="#FD1B14" stroke="#000000" stroke-width="1"/>

        <!-- 9-RING -->
        <circle cx="300" cy="300" r="79" fill="#FFE552" stroke="#000000" stroke-width="1"/>

        <!-- 10-RING -->
        <circle cx="300" cy="300" r="39" fill="#FFE552" stroke="#000000" stroke-width="1"/>

        <!-- INNER 10-RING -->
        <circle cx="300" cy="300" r="19" fill="#FFE552" stroke="#000000" stroke-width="1"/>

        <g class="spider">
          <line x1="295" y1="300" x2="305" y2="300" stroke="#000000" stroke-width="1"/>
          <line x1="300" y1="295" x2="300" y2="305" stroke="#000000" stroke-width="1"/>
        </g>
      </g>
    </svg>

produces

<div style="height: 400px; width: 400px;">
<svg id="svg_wa_6_zone" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" height="100%" width="100%" viewBox="0 0 600 600">

  <g>
    <!-- 5-RING -->
    <circle cx="300" cy="300" r="239" fill="#00B4E4"/>

    <!-- 6-RING -->
    <circle cx="300" cy="300" r="199" fill="#00B4E4" stroke="#000000" stroke-width="1"/>

    <!-- 7-RING -->
    <circle cx="300" cy="300" r="159" fill="#FD1B14" stroke="#000000" stroke-width="1"/>

    <!-- 8-RING -->
    <circle cx="300" cy="300" r="119" fill="#FD1B14" stroke="#000000" stroke-width="1"/>

    <!-- 9-RING -->
    <circle cx="300" cy="300" r="79" fill="#FFE552" stroke="#000000" stroke-width="1"/>

    <!-- 10-RING -->
    <circle cx="300" cy="300" r="39" fill="#FFE552" stroke="#000000" stroke-width="1"/>

    <!-- INNER 10-RING -->
    <circle cx="300" cy="300" r="19" fill="#FFE552" stroke="#000000" stroke-width="1"/>

    <g class="spider">
      <line x1="295" y1="300" x2="305" y2="300" stroke="#000000" stroke-width="1"/>
      <line x1="300" y1="295" x2="300" y2="305" stroke="#000000" stroke-width="1"/>
    </g>
  </g>
</svg>
<div>


## License

SVG Target Faces published under MIT License
