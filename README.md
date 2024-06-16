# robots

<script>
    document.addEventListener('DOMContentLoaded', function () {
        const deleteButton = document.querySelector('.delete-robot');
        const confirmDialog = document.querySelector('.confirm-delete');
        const cancelButton = document.querySelector('.cancel-delete');

        deleteButton.addEventListener('click', function () {
            confirmDialog.showModal();
        });

        cancelButton.addEventListener('click', function () {
            confirmDialog.close();
        });
    });
</script>
