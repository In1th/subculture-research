<script>
    const onSubmit = () => {
        showForm = false
    }
    let showForm = true;
</script>

<main>
    <h1>In what subculture do you belong?</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ab iure doloribus facilis corrupti, atque aliquam vel, libero dignissimos rerum culpa animi veniam veritatis. Error laudantium quibusdam ducimus cupiditate sunt enim?</p>
    <br/>
    {#if showForm}
         <form on:submit={onSubmit}>
             <label for='age'>Age</label>
             <select id='age'>
                 <option>less than 14yo</option>
                 <option>15-17 yo</option>
                 <option>18-20 yo</option>
                 <option>21-23 yo</option>
                 <option>24-26 yo</option>
                 <option>27-29 yo</option>
                 <option>30-32 yo</option>
                 <option>33-35 yo</option>
                 <option>more than 36 yo</option>
             </select>
             <label for='gender'>Gender</label>
             <select id='gender'>
                 <option>male</option>
                 <option>female</option>
                 <option>other</option>
                 <option>prefer not to say</option>
             </select>
             <label for='sex'>Sexual identity</label>
             <select id='sex'>
                 <option>heterosexual</option>
                 <option>homosexual</option>
                 <option>asexual</option>
                 <option>pansexual</option>
                 <option>demisexual</option>
                 <option>bisexual</option>
             </select>
             <label for='rel'>Relationship status</label>
             <select id='rel'>
                 <option>single</option>
                 <option>in a closed relationship</option>
                 <option>in a open relationship</option>
                 <option>engaged</option>
                 <option>married</option>
             </select>
             <div>
                 <input id='father-figure' type="checkbox"/>
                 <label for='father-figure'>Did you have a father figure growing up?</label>
             </div>
             <label for='type-person'>Type of person</label>
             <select id='type-person'>
                 <option>introvert</option>
                 <option>extrovert</option>
                 <option>ambivert</option>
             </select>
             <div>
                 <input id='agreeable' type="number" max="7" min="1" value="1">
                 <label for="agreeable">On a scale of 1 - 7, how agreeable do you think you are?</label>
             </div>
             <div>
                 <input id='self-aware' type="number" max="7" min="1" value="1">
                 <label for="self-aware">On a scale of 1 - 7, how self-aware do you think you are?</label>
             </div>
             <div>
                 <input id='emotionally-stable' type="number" max="7" min="1" value="1">
                 <label for="emotionally-stable">On a scale of 1 - 7, how emotionally stable do you think you are?</label>
             </div>
             <div>
                 <input id='new-experiences' type="number" max="7" min="1" value="1">
                 <label for="new-experiences">On a scale of 1 - 7, how much are you open to new experiences?</label>
             </div>
             <label for='hard-comm'>Do you find it hard to communicate with other people?</label>
             <select id='hard-comm'>
                 <option>Yes</option>
                 <option>No</option>
                 <option>Maybe</option>
             </select>
             <label for='understand-ppl'>Do you find it hard to understand how other people think or feel?</label>
             <select id='understand-ppl'>
                 <option>Yes</option>
                 <option>No</option>
                 <option>Maybe</option>
             </select>
             <label for='anxious'>Do you get anxious in social situations?</label>
             <select id='anxious'>
                 <option>Yes</option>
                 <option>No</option>
                 <option>Maybe</option>
             </select>
             <label for='education'>What is your highest education</label>
             <select id='education'>
                 <option>primary/secondary school</option>
                 <option>high school</option>
                 <option>technical degree</option>
                 <option>bachelor's degree</option>
                 <option>master's degree</option>
                 <option>doctorate</option>
             </select>
             <label for='employement'>What is your employment status?</label>
             <select id='employement'>
                 <option>I'm working</option>
                 <option>I'm studying</option>
                 <option>I'm a working student</option>
                 <option>I'm unemployed</option>
             </select>
             <label for='type-job'>What is your employment status?</label>
             <select id='type-job'>
                 <option>retail worker</option>
                 <option>restaurant worker</option>
                 <option>office worker</option>
                 <option>artist</option>
                 <option>construction/physical worker</option>
                 <option>management</option>
                 <option>marketing</option>
                 <option>public services</option>
                 <option>education-related job</option>
                 <option>enterprenour</option>
             </select>
             <div>
                 <input id='hanging-out' type="number" max="7" min="1" value="1">
                 <label for="hanging-out">On a scale of 1 - 7, how much do you enjoy hanging out with friends outside?</label>
             </div>
             <label for='social-media'>What social media platform are you using the most?</label>
             <select id='social-media'>
                 <option>Discord</option>
                 <option>Telegram</option>
                 <option>Facebook</option>
                 <option>Messenger</option>
                 <option>WhatsUp</option>
                 <option>Snapchat</option>
                 <option>Twitter</option>
                 <option>Instagram</option>
                 <option>VR Chat</option>
                 <option>Reddit</option>
             </select>
             <label for='ppl-interact'>With what age group of people do you prefer to interact?</label>
             <select id='ppl-interact'>
                 <option>less than 18 yo</option>
                 <option>18-20 yo</option>
                 <option>21-24 yo</option>
                 <option>25-30 yo</option>
                 <option>30-45 yo</option>
                 <option>more than 45 yo</option>
             </select>
             <label for='phone-usage'>How much do you use your smartphone per day?</label>
             <select id='phone-usage'>
                 <option>less than 1h</option>
                 <option>1-2h</option>
                 <option>3-4h</option>
                 <option>6-8h</option>
                 <option>more than 8h</option>
                 <option>I have an old phone</option>
             </select>
             <label for='pc-usage'>How much do you use your computer?</label>
             <select id="pc-usage">
                 <option>less than 1h</option>
                 <option>1-2h</option>
                 <option>3-4h</option>
                 <option>6-8h</option>
                 <option>more than 8h</option>
                 <option>I don't use a computer</option>
             </select>
             <p>What type of media are you consuming?</p>
             <div>
                 <input id='media-tv' type="checkbox">
                 <label for="media-tv">Television</label>
             </div>
             <div>
                 <input id='media-yt' type="checkbox">
                 <label for="media-yt">YouTube</label>
             </div>
             <div>
                 <input id='media-tk' type="checkbox">
                 <label for="media-tk">Tiktok</label>
             </div>
             <div>
                 <input id='media-nt' type="checkbox">
                 <label for="media-nt">Netflix</label>
             </div>
             <div>
                 <input id='media-oth' type="checkbox">
                 <label for="media-oth">Other streaming services (HBO MAX, Disney +, Hulu, Amazon Prime, etc.)levision</label>
             </div>
             <div>
                 <input id='media-str' type="checkbox">
                 <label for="media-str">Stream content (Twitch, Youtube, Kick)</label>
             </div>
             <input type="submit" value="Submit">
         </form>
    {:else}
        <h3>You are a furry</h3>
        <button on:click={() => showForm=true}>Reset</button>
    {/if}
</main>

<style>
    main {
        padding-inline: 1rem;
    }
    form {
        display: flex;
        flex-direction: column;
        gap: .5rem;
    }
    p {
        margin: 0;
    }
</style>