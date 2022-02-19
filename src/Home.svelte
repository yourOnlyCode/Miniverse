

<label class="btn" for="modal-1">Login</label>
<input class="modal-state" id="modal-1" type="checkbox" />
<div class="modal">
    <p style="color:black">Login not yet available for public.</p>
    <p style="color:black">Get notified for public launch:</p>

    <a href="https://forms.gle/VPKkh41koqduevZW8">Click Here</a>
</div>

<style>
.modal {
    display: flex;
    width: 66%;
    justify-content: center;
  opacity: 0;
  visibility: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  text-align: left;
  background: rgba(0,0,0, .9);
  transition: opacity .25s ease;
}    

.modal-state {
  display: none;
}

.modal-state:checked + .modal {
  opacity: 1;
  visibility: visible;
}
</style>