<template>
  <div class="hello">
    <div class="container">
      <div>
        <h2>Jquery To Do List</h2>
        <p>
          <em>Simple Todo List with adding and filter by diff status.</em>
        </p>
      </div>
      <div>
        <input class="input-text" type="text" name="ListItem" />
        <div id="button">Add</div>
      </div>
      <br />
      <ol>
        <li id class="checked">
          <input name="done-todo" checked type="checkbox" class="done-todo" />
          <span>a</span>
        </li>
        <li id class>
          <input name="done-todo" type="checkbox" class="done-todo" />
          <span>a</span>
        </li>
      </ol>
      <div>
        <ul id="filters">
          <li>
            <a href="#" data-filter="all" class="selected">ALL</a>
          </li>
          <li>
            <a href="#" data-filter="active" class>Active</a>
          </li>
          <li>
            <a href="#" data-filter="complete" class>Complete</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>