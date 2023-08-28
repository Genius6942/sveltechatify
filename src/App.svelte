<script lang="ts">
  import "./app.css";

  import { SignedIn, SignedOut, Doc, Collection } from "sveltefire";
	
  import { signInAnonymously } from "firebase/auth";
</script>


<FirebaseApp {auth} {firestore}>
	
</FirebaseApp>