<script>
	import Day from './Day.svelte';
</script>

<div class="flex flex-col">
	<div class="overflow-x-auto sm:-mx-6 lg:-mx-8">
		<div class="py-2 inline-block min-w-full sm:px-6 lg:px-8">
			<div class="overflow-hidden">
				<table class="min-w-full">
					<thead class="border-b">
						<tr>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left"> # </th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Sunday
							</th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Munday
							</th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Tuesday
							</th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Wednesday
							</th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Thursday
							</th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Friday
							</th>
							<th scope="col" class="text-sm font-medium text-gray-900 px-6 py-4 text-left">
								Saturday
							</th>
						</tr>
					</thead>
					<tbody>
						<tr class="border-b">
							<td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">1</td>
							<Day />
							<Day />
							<Day />
							<Day />
							<Day />
							<Day />
							<Day />
						</tr>
					</tbody>
				</table>
			</div>
		</div>
	</div>
</div>
