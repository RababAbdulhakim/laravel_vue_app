<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">Users 
<div class="card-tools">
<button> Add new <i class='fa fa-user'></i> </button>
</div>
 </div>
<div class="box-body table-responsive no-padding">
              <table class="table table-hover">
                <tbody><tr>
                  <th>ID</th>
                  <th>Name</th>
                  <th>Email</th>
                  <th>Type</th>
                  <th>Edit</th>
                </tr>
                <tr>
                  <td>183</td>
                  <td>John Doe</td>
                  <td>11-7-2014</td>
                  <td>user</td>
                  <td><a href='#'>
                       <i class= 'fa fa-edit'></i>
</a>
<a href='#'>
                       <i class= 'fa fa-trash'></i>
</a></td>
                </tr>
                
              </tbody></table>
            </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
