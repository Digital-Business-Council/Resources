# Resources

This is a temporary repository to hold the technical files referenced in version 1.0 of the Interoperability Framework and its Implementation Guides.

This will be replaced in forthcoming versions of each Implementation guide with direct links to GitHub repositories.

## File Structure

{% for file in site.static_files %}
  <a href="{{ file.path }}">{{ file.path }}</a>
{% endfor %}
