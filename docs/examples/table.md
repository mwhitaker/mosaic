<script setup>
  import { reset } from '@uwdata/vgplot';
  reset();
</script>

# Sortable Table

A sortable, "infinite scroll" `table` view over a backing database table. Click column headers to sort, or command-click to reset the order. Data is queried as needed as the table is sorted or scrolled.

<Example spec="/specs/yaml/table.yaml" />

## Specification

::: code-group
<<< @/public/specs/esm/table.js [JavaScript]
<<< @/public/specs/yaml/table.yaml [YAML]
<<< @/public/specs/json/table.json [JSON]
:::
