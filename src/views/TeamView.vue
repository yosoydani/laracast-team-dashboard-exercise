<script setup>
</script>

<template>
  <header class="flex justify-between">
    <div>
      <button class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded disabled:bg-gray-400" :disabled="true">Add Member (0 Spots Left)</button>
    </div>
    <div>
      <div class="inline-flex items-center text-3xl relative">
        <img src="/smiley.png" alt="" class="mr-2">
        <h3>Smiley Team</h3>
        <div class="bg-green-400 w-5 h-5 text-xs text-white rounded-full flex justify-center items-center absolute -right-4 -top-2">5</div>
      </div>
    </div>
  </header>

  <div class="place-self-center flex flex-col gap-y-3">
    <table class="table-fixed border-spacing-2 border-separate">
      <thead>
      <th class="text-left px-6 py-2">Name</th>
      <th class="text-left px-6 py-2">Email</th>
      <th class="text-left px-6 py-2">Status</th>
      </thead>
      <tbody>
      <tr class="bg-gray-100 px-12">
        <td class="text-xl font-medium flex items-center gap-x-4 px-6 py-4">
          <img src="https://i.pravatar.cc/50?u=john@doe.com" alt="" class="rounded-full">
          John Doe
        </td>
        <td class="text-gray-500 px-6 py-4">john@doe.com</td>
        <td class="px-6 py-4">
          <button class="text-green-400 text-xl">Active</button>
        </td>
      </tr>

      <tr class="bg-gray-100 px-12">
        <td class="text-xl font-medium flex items-center gap-x-4 px-6 py-4">
          <img src="https://i.pravatar.cc/50?u=sarah@doe.com" alt="" class="rounded-full">
          Sarah Doe
        </td>
        <td class="text-gray-500 px-6 py-4">sarah@doe.com</td>
        <td class="px-6 py-4">
          <button class="text-green-400 text-xl">Active</button>
        </td>
      </tr>

      <tr class="bg-gray-100 px-12">
        <td class="text-xl font-medium flex items-center gap-x-4 px-6 py-4">
          <img src="https://i.pravatar.cc/50?u=steven@doe.com" alt="" class="rounded-full">
          Steven Doe
        </td>
        <td class="text-gray-500 px-6 py-4">steven@doe.com</td>
        <td class="px-6 py-4">
          <button class="text-green-400 text-xl">Active</button>
        </td>
      </tr>

      <tr class="bg-gray-100 px-12">
        <td class="text-xl font-medium flex items-center gap-x-4 px-6 py-4">
          <img src="https://i.pravatar.cc/50?u=jen@doe.com" alt="" class="rounded-full">
          Jen Doe
        </td>
        <td class="text-gray-500 px-6 py-4">jen@doe.com</td>
        <td class="px-6 py-4">
          <button class="text-green-400 text-xl">Active</button>
        </td>
      </tr>

      <tr class="bg-gray-100 px-12">
        <td class="text-xl font-medium flex items-center gap-x-4 px-6 py-4">
          <img src="https://i.pravatar.cc/50?u=joe@doe.com" alt="" class="rounded-full">
          Joe Doe
        </td>
        <td class="text-gray-500 px-6 py-4">joe@doe.com</td>
        <td class="px-6 py-4">
          <button class="text-green-400 text-xl">Active</button>
        </td>
      </tr>

      </tbody>
    </table>
    <p class="text-right text-gray-600 italic">There are no remaining team spots. Upgrade to add more.</p>
  </div>
  <footer class="mt-12 bg-gray-100 py-4 text-center">
    <h5 class="font-semibold text-lg">Smiley - 5 Member Team</h5>
  </footer>
</template>
