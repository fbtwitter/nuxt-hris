<template>
  <div>
    <section class="py-[70px] flex flex-col items-center justify-center px-4">
      <div class="text-[32px] font-semibold text-dark">New Role</div>
      <p class="mt-4 text-base leading-7 text-center mb-[50px] text-grey">
        Manage your employees to achieve <br />
        a bigger goals for your company
      </p>
      <form class="w-full card">
        <div class="form-group">
          <label for="" class="text-grey">Role Name</label>
          <input type="text" class="input-field" value="Product Marketing" />
        </div>
        <div class="form-group">
          <label for="idRes" class="text-grey">Responsibility</label>
          <ul id="listResp" class="flex flex-col gap-4">
            <li class="inline-flex items-center w-full gap-5">
              <input
                id="idRes"
                type="text"
                name="responsibility"
                class="w-full input-field"
              />
              <a id="addRsp" href="#" role="button">
                <img src="/assets/svgs/ric-plus.svg" alt="" />
              </a>
            </li>
          </ul>
        </div>
        <a href="roles.html" class="w-full btn btn-primary mt-[14px]">
          Save Role
        </a>
      </form>
    </section>
  </div>
</template>

<script>
export default {
  layout: 'form',
}
</script>
