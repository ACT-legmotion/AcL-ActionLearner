# AcL-ActionLearner

## VIDEOS

### Teacher Polices Shown in Gazebo

### Real World Deployment

<table align="center">
    <tr>
        <td align="center" width="33%">
            <img src="video&pics/LR.gif" width="100%" height="auto">
            <p>The quadruped can adaptively switch its gait when faults occur and are resolved without any command given. (Faults on LR)</p>
        </td>
        <td align="center" width="33%">
            <img src="video&pics/RR.gif" width="100%" height="auto">
            <p>The quadruped can adaptively switch its gait when faults occur and are resolved without any command given. (Faults on RR)</p>
        </td>
        <td align="center" width="33%">
            <img src="video&pics/KICKING.gif" width="100%" height="auto">
            <p>The quadruped can resist kicking.</p>
        </td>
    </tr>
    <tr>
        <td align="center" width="33%">
            <img src="video&pics/LOADING.gif" width="100%" height="auto">
            <p>The quadruped can stably load parcels. (This parcel is 1.1kg and not strictly fixed on the quadruped)</p>
        </td>
        <td align="center" width="33%">
            <img src="video&pics/CROSS.gif" width="100%" height="auto">
            <p>The quadruped can cross surfaces with different textures in a single locomotion task.</p>
        </td>
    </tr>
</table>



## TODO
- Training configs for teacher policies
- Training codes for both teacher policies and the student policy based on [legged_gym](https://github.com/leggedrobotics/legged_gym) and [rsl_rl](https://github.com/leggedrobotics/rsl_rl)
- Checkpoints for teacher policies, encoder, and decoder
- Sim2real suitable for loosing-torque faults manipulation based on [rl_sar](https://github.com/fan-ziqi/rl_sar)

## ASKING FOR HELP
We’re afraid of damaging the quadruped, so we haven’t tested the standing and hand-standing gaits in real cases yet. We will sincerely appreciate it if someone can share checkpoints/training configs that are tested to be valid for Go2 standing and hand-standing in real cases for these two gaits!

