<template>
<div class="_gaps">
	<div style="text-align: center; padding: 0 16px;">{{ i18n.ts._initialTutorial._private.description }}</div>
	<div class="_gaps_s">
		<div>
			<b>{{ i18n.ts._initialTutorial._private.restriction_title }}</b> … <div>
				{{ i18n.ts._initialTutorial._private.restriction_description_1 }}<br>
				{{ i18n.ts._initialTutorial._private.restriction_description_2 }}<br>
				{{ i18n.ts._initialTutorial._private.restriction_description_3 }}
			</div>
		</div>
		<div>
			<b>{{ i18n.ts._initialTutorial._private.member_title }}</b> … <div>
				{{ i18n.ts._initialTutorial._private.member_description_1 }}<br>
				{{ i18n.ts._initialTutorial._private.member_description_2 }}
			</div>
		</div>
		<div>
			<b>{{ i18n.ts._initialTutorial._private.invitation_title }}</b> … <div>
				{{ i18n.ts._initialTutorial._private.invitation_description_1 }}<br>
				{{ i18n.ts._initialTutorial._private.invitation_description_2 }}<br>
				{{ i18n.ts._initialTutorial._private.invitation_description_3 }}<br>
				{{ i18n.ts._initialTutorial._private.invitation_description_4 }}
			</div>
		</div>
	</div>
</div>
</template>

<script setup lang="ts">
import { i18n } from '@/i18n.js';

</script>
