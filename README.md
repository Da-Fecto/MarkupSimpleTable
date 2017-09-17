# MarkupSimpleTable
ProcessWire module for generating table markup

```php
$table = $modules->get('MarkupSimpleTable');

$table->setSection('thead');
$table->tr();
$table->th('value', 'classname', array('id' => 'th-id'));
$table->th('value');
$table->th('value');
$table->th('value');

$table->setSection('tbody');
$table->tr();
$table->td('value');
$table->td('value');
$table->td('value');
$table->td('value');

$table->setSection('tfoot');
$table->tr();
$table->td('value');
$table->td('value');
$table->td('value');
$table->td('value');
```
