# Documents

the following is a list of PCTF documents available for download

<ul>
  {% for item in site.static_files -%}
  {%- assign arr = item.path | split: "/" -%}
  {%- if arr[1] == "docs" -%}
  {%- if arr.size == 3 -%}
  {%- if prevSize == 4 -%}
    </ul>
  </li>
  {%- endif -%}
  <li>
    <a href="{{item.path}}">{{item.name}}</a>
  </li>
  {%- endif -%}
  {%- if arr.size == 4 -%}
  {%- unless prevSize == 4 -%}
  <li>
    {{-arr[2]-}}
    <ul>
  {%- endunless %}
    <li>
      <a href="{{item.path}}">{{item.name}}</a>
    </li>
  {%- endif -%}
  {%- assign prevSize = arr.size -%}
  {%- endif -%}
  {%- endfor %}
</ul>
