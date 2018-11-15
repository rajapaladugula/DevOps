# DevOps Documents
This contains various documents related to ad hoc DevOps Tasks.

<table>
  <tr>
    <th>Type</th>
    <th>Tools</th>
    <th>Description</th>
    <th>Comments</th>
  </tr>
  <tr>
    <td><code>Cloud</code></td>
    <td>AWS</td>
    <td>Amazon Web Services.</td>
    <td></td>
  </tr>
  <tr>
    <td><code>Configuration Management</code></td>
    <td>Chef</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><code>Continous Integration</code></td>
    <td>Jenkins | Bamboo</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Database</code></td>
    <td>SQL</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Containerization</code></td>
    <td>DockerL</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>ELK</code></td>
    <td>Elastic Search, Log statsh, Kibana, Watchers</td>
    <td></td>
    <td></td>
  </tr><tr>
    <td>Linux</code></td>
    <td>CentOs</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Programming</code></td>
    <td>SQL</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Source Code Management</code></td>
    <td>L</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Windowse</code></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Others</code></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></code></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

# Usage

Include `'metric_beat::default'` to your runlist. This will install Metric Beat, which will be installed from Zip file.

This will install all the available MetricBeat versions in this cookbook:
```ruby
include_recipe 'metric_beat'
```

If you want to install a specific version of the MetricBeat, include only that particular recipe.

This will install only MetricBeat:
```ruby
include_recipe 'metric_beat::MetricBeat'
```

# Recipes

## default
It installs all the available MetricBeat versions in this cookbook i.e 6.4.2 . You should add this recipe to your run list.

# TO DO

- Developing test cases.
- Develop cook books for other versions of Metric Beat.
