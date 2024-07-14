trigger Account_Mirror on Account (after insert, after update) {

    if (Trigger.isAfter && Trigger.isInsert) {
        AccountMirrorHandler.AccountMirrorInsert(Trigger.new);
    }
    if (Trigger.isAfter && Trigger.isUpdate) {
        AccountMirrorHandler.AccountMirrorUpdate(Trigger.new);
    }
}
