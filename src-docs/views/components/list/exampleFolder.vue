<template>
<mobile-tear-sheet>
  <mu-list>
    <mu-sub-header inset>Folders</mu-sub-header>
    <mu-list-item title="Photos" describeText="Jan 9, 2014">
      <mu-avatar icon="folder" slot="rightAvatar"/>
      <mu-icon value="info" slot="left"/>
    </mu-list-item>
    <mu-list-item title="Recipes" describeText="Jan 17, 2014">
      <mu-avatar icon="folder" slot="rightAvatar"/>
      <mu-icon value="info" slot="left"/>
    </mu-list-item>
    <mu-list-item title="Work" describeText="Jan 28, 2014">
      <mu-avatar icon="folder" slot="rightAvatar"/>
      <mu-icon value="info" slot="left"/>
    </mu-list-item>
  </mu-list>
  <mu-divider inset/>
  <mu-list>
    <mu-sub-header inset>Files</mu-sub-header>
    <mu-list-item title="Vacation itinerary" describeText="Jan 20, 2014">
      <mu-avatar icon="assignment" backgroundColor="blue" slot="rightAvatar" />
      <mu-icon value="info" slot="left"/>
    </mu-list-item>
    <mu-list-item title="Kitchen remodel" describeText="Jan 10, 2014">
      <mu-avatar icon="insert_chart" backgroundColor="yellow600" slot="rightAvatar" />
      <mu-icon value="info" slot="left"/>
    </mu-list-item>
  </mu-list>
</mobile-tear-sheet>
</template>

<script>
import mobileTearSheet from '../../../components/mobileTearSheet'
export default {
  components: {
    'mobile-tear-sheet': mobileTearSheet
  }
}
</script>
